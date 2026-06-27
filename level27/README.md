# Bandit Level 26 → Level 27

### 🔑 Objective
Clone a remote Git repository hosted locally on the challenge system over SSH and extract the plain-text password from the repository tracking data.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Clone the target repository configuration directly from localhost
git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo /tmp/repo_27

# Step 2: Navigate inside the cloned directory map and read the readme file
cd /tmp/repo_27
cat README

# Password: upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB
