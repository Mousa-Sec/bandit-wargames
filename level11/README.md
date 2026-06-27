# Bandit Level 10 → Level 11

### 🔑 Objective
Decode the target password file (`data.txt`) which has been heavily encoded using Base64 translation format.

### 🛠️ Core Command Blueprint
```bash
# Read the file and pass it directly through the base64 decoding module
cat data.txt | base64 --decode
# Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
