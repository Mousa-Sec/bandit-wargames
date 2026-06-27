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
├── level04/         # File type evaluation & ASCII text isolation
├── level05/         # Recursive directory size & attribute filtering
├── level06/         # System-wide multi-criteria user/group asset hunting
├── level07/         # Text pattern filtering via stream pipelining (grep)
├── level08/         # Array line sorting & unique frequency extraction
├── level09/         # Extracting human-readable strings from raw binaries
├── level10/         # Parsing hidden indicator flags in mixed clutter
├── level11/         # Reversing Base64 binary-to-text data translations
├── level12/         # Defeating alphabetic rotation ciphers (ROT13)
├── level13/         # Hexdump reversal & multi-tier archive decompression
├── level14/         # Cryptographic asymmetric private key verification
├── level15/         # Network socket I/O communication over TCP ports
├── level16/         # Encrypted transport layer security (TLS/SSL) tunnels
├── level17/         # Differential byte-level file comparison analysis (diff)
├── level18/         # Non-interactive shell command injection overrides
├── level19/         # Privilege interception via SetUID file descriptors
├── level20/         # Socket daemon simulation & background pipe manipulation
├── level21/         # Enumerating scheduled cron tasks for temporary logs
├── level22/         # Reversing deterministic cryptographic MD5 user hashes
├── level23/         # Custom automated cron spool exploitation scripts
├── level24/         # Automated loop brute-forcing over raw loopback ports
├── level25/         # Restricted shell escapes via terminal pager overflow
├── level26/         # Elevated data extraction using contextual wrapper modules
├── level27/         # Local internal repository cloning configurations
├── level28/         # Auditing historical transaction logging configurations
├── level29/         # Branch segregation & unmerged commit data discovery
├── level30/         # Metadata release anchor tag forensic discovery
├── level31/         # Overriding system configuration exclusion lists (.gitignore)
├── level32/         # POSIX variable token substitution escapes ($0)
└── level33/         # Sub-shell tracking & milestone completion validation
