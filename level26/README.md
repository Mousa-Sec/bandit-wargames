# Bandit Level 25 → Level 26

### 🔑 Objective
Leverage an administrative SetUID executable stashed within the newly escaped terminal environment to grab the final level credentials.

### 🛠️ Core Command Blueprint
```bash
# Execute the custom SUID wrapper to stream password payloads with elevated access permissions
./bandit27-do cat /etc/bandit_pass/bandit27

# Password: s0773xxkk0MXfdq0fPRVr9L3jJBUOgCZ
