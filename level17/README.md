# Bandit Level 16 → Level 17

### 🔑 Objective
Identify the only single line of text that has been changed between two server configuration inventory mappings: `password.old` and `password.new`.

### 🛠️ Core Command Blueprint
```bash
# Compare the line variations between the old and new file sets
diff password.old password.new
# Password: kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
