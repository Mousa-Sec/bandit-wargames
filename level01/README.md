# Bandit Level 0 → Level 1

### 🔑 Objective
Log into the remote OverTheWire game server using Secure Shell (SSH) and read the initial credentials file to pass the first stage.

### 🛠️ Core Command Blueprint
```bash
# Connect to the game server via custom port 2220
ssh -p 2220 bandit0@bandit.labs.overthewire.org

# Read the cleartext password file inside the home directory
cat readme
# Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
