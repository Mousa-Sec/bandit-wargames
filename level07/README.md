# Bandit Level 6 → Level 7

### 🔑 Objective
Search the entire server operating system filesystem for a target matching specific configuration flags: User `bandit7`, Group `bandit6`, and an exact size of 33 bytes.

### 🛠️ Core Command Blueprint
```bash
# Scan system root and throw errors into standard black hole storage
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
# Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
