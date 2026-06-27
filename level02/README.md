# Bandit Level 1 → Level 2

### 🔑 Objective
Extract the hidden credential stored within a file sitting in the home directory named exactly with a hyphen character `-`.

### 🛠️ Core Command Blueprint
```bash
# Explicitly query the relative file token to bypass the options parser
cat ./-
# Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
