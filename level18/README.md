# Bandit Level 17 → Level 18

### 🔑 Objective
Bypass an aggressive automated interactive shell logout trap (`.bashrc` kick-out configuration) by passing a direct command parameter over an SSH connection utilizing a private key file.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Save the RSA Private Key block into a local file named bandit17.key
nano bandit17.key

# Step 2: Restrict file permissions so SSH allows the key to be loaded
chmod 600 bandit17.key

# Step 3: Authenticate using the key (-i) and append a command string to read the password
ssh -i bandit17.key bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"
