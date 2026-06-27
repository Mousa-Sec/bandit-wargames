# 🏁 OverTheWire: Bandit Wargames

A structured, high-fidelity repository documenting practical solutions, Linux administration fundamentals, and security concepts encountered throughout the **OverTheWire Bandit** CTF challenge series.

---

## 🛠️ Core Skills & Security Vectors Demonstrated

This project serves as an interactive playground showcasing key competencies in Linux operating system environments and fundamental security engineering concepts:

* **Linux System Administration:** Deep familiarity with POSIX file boundaries, permission access masks (`chmod`, `chown`, SetUID binaries), system configurations (`/etc/passwd`), and background task managers (`cron`, `cron.d`).
* **Advanced Data Piping & Filtering:** Mastery of intermediate Linux data text streaming utilities (`grep`, `awk`, `tr`, `sort`, `uniq`, `strings`, `xxd`) to parse noise out of corrupt or massive binary blobs.
* **Network Tunnelling & Socket I/O:** Establishing secure terminal loops, identifying socket vectors (`nmap`), interacting with raw TCP ports over custom background daemons (`netcat`), and managing encrypted data streams (`OpenSSL s_client`).
* **Cryptographic Analysis:** Interacting with Base64 encoding schemas, evaluating differential metrics between file sets (`diff`), and implementing deterministic cryptographic hash functions (`md5sum`).
* **Git Forensic Auditing:** Mining historical repository transaction logs (`git log`, `git show`), managing alternate project branches (`git branch`), inspecting release structures (`git tag`), and debugging repository configuration constraints (`.gitignore`).

---

## 📂 Repository Architecture

The workspace utilizes a strictly organized, padded chronological directory model. Each module has been completely refactored to house a standalone, high-grade documentation hub detailing the forensic steps, command blueprints, and core concepts discovered at that specific stage:

```text
bandit-wargames/
├── level01/         # Relative path boundaries & special characters
├── level02/         # Shell tokenization & space handling ciphers
├── level03/         # Hidden dotfile disclosure mechanics
├── ...
├── level24/         # Automated background cron spool exploit vectors
├── level25/         # Socket manipulation & multi-combination brute forcing
└── level26/         # Restricted shell escapes via terminal pager overflow (Vim)
