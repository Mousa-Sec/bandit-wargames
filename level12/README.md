# Bandit Level 11 → Level 12

### 🔑 Objective
Decrypt a file where all lowercase and uppercase letters have been rotated by 13 positions using a custom substitution cipher (ROT13).

### 🛠️ Core Command Blueprint
```bash
# Translate alphabetic arrays across the 13-space character rotation map
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
# Password: 7x16WNeHIi5YkIhWsffIqoognUTyj9Q4
