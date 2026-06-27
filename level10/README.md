# Bandit Level 9 → Level 10

### 🔑 Objective
Extract the plain-text password embedded inside a file containing mixed binary clutter, prefixed with several `=` data characters.

### 🛠️ Core Command Blueprint
```bash
# Filter character sequences and search for the indicator pattern
strings data.txt | grep "=="
# Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
