# Bandit Level 18 → Level 19

### 🔑 Objective
Leverage a custom binary configuration possessing SetUID permissions in the user home environment to read privileged target directories.

### 🛠️ Core Command Blueprint
```bash
# Invoke the localized SUID utility to execute file reads with owner context
./bandit20-do cat /etc/bandit_pass/bandit20

# Password: cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
