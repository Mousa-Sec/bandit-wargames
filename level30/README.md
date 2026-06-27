# Bandit Level 29 → Level 30

### 🔑 Objective
Locate hidden password variables stashed inside an alternative repository metadata pointer called a Git tag.

### 🛠️ Core Command Blueprint
```bash
# Step 1: List all historical anchor tags applied to the workspace
git tag

# Step 2: Show the raw metadata contents bound to that specific tag name reference
git show secret

# Password: qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
