# Bandit Level 14 → Level 15

### 🔑 Objective
Transmit the current session credential safely over a local connection pipe to a network daemon listening on local TCP Port 30000.

### 🛠️ Core Command Blueprint
```bash
# Pipe the active secret directly down into the target TCP port pipeline
nc localhost 30000
# Password: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
