# Bandit Level 30 → Level 31

### 🔑 Objective
Push a text file named exactly `key.txt` into a master remote repository branch while bypassing an active system ignore list configuration (`.gitignore`).

### 🛠️ Core Command Blueprint
```bash
# Step 1: Edit the local exclusion matrix file to strip out constraints
nano .gitignore

# Step 2: Create the file layout exactly as instructed
echo "may I come in" > key.txt

# Step 3: Bundle, stage, commit, and push changes live to origin master
git add key.txt
git commit -m "Submit validation criteria"
git push origin master

# Password: fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy
