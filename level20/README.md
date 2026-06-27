# Bandit Level 19 → Level 20

### 🔑 Objective
Establish an active local server daemon listener inside a background session and trick an external validation script into authenticating with your environment.

### 🛠️ Core Command Blueprint
```bash
# Step 1: Open a local listening socket pipeline in a separate console window
nc -l -p 12345

# Step 2: Pass the target socket target parameters to the automated validator binary
./suconnect 12345

# Password: 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
