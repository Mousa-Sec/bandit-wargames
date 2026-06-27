# Bandit Level 3 → Level 4

### 🔑 Objective
Navigate into a directory structure and expose a hidden configuration file to retrieve the password.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Move into the hidden target directory
cd inhere

# Step 2: List all directory properties including hidden items
ls -la

# Step 3: Stream the contents of the hidden target file
cat .hidden
# Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
