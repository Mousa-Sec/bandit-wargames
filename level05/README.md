# Bandit Level 4 → Level 5

### 🔑 Objective
Identify the single human-readable ASCII text file hidden inside a directory full of non-ascii binary data clusters.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Run file analysis across all targets in the directory
file ./*

# Step 2: Read the isolated plain-text target file
cat ./file07
# Password:4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
