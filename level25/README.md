# Bandit Level 24 → Level 25

### 🔑 Objective
Authenticate seamlessly into a restricted account environment where the default user shell (`/usr/bin/showtext`) has been changed from standard `bash` to limit terminal usage.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Enumerate system account shell tracking entries to spot restrictions
cat /etc/passwd | grep "bandit26"

# Step 2: Compress the terminal window layout to artificially force a text overflow page trigger
# Step 3: Run the SSH private key connection profile
ssh -i bandit26.sshkey bandit26@localhost -p 2220

# Step 4: When the terminal hits the "More" boundary prompt, press 'v' to jump directly into Vim text editor controls
# Step 5: Inside the Vim session command editor path, escape the restricted environment shell:
:set shell=/bin/bash
:shell
# Password: iCi86ttT4KSNe1armKiwbQNmB3YJP3q4
