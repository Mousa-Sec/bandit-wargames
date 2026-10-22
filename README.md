# OverTheWire: Bandit Wargame

> **Note:** Level passwords and SSH keys are redacted on purpose. Committing credentials to a public repo is bad practice, even for a wargame.

My solutions and notes for the [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) wargame, levels 0 to 33. Each folder covers one level: the goal, the commands I used, and the concept behind it.

---

## What this covers

* **Linux files and permissions:** special and hidden filenames, finding files by size, owner and group, and using SetUID binaries to run commands as another user.
* **Text processing:** `grep`, `sort`, `uniq`, `strings`, `tr`, `base64` and `xxd`, plus unpacking a file compressed many times over.
* **Networking:** logging in with SSH keys, talking to services with `netcat`, connecting over TLS with `openssl s_client`, and scanning for listening ports with `nmap`.
* **Scheduled tasks:** reading cron jobs to work out what they do, then writing a script for a cron job to run.
* **Shell escapes:** breaking out of a restricted shell through a pager, and through `$0`.
* **Git:** recovering data from commit history, branches and tags, and working around `.gitignore`.
* **Automation:** a Bash loop to brute-force a 4-digit PIN against a local service.

---

## Repository layout

Folder `levelNN` covers the step from level NN-1 to level NN.

```text
bandit-wargames/
├── level01/   # 0 → 1:   log in over SSH and read a file
├── level02/   # 1 → 2:   read a file named "-"
├── level03/   # 2 → 3:   read a file with spaces in its name
├── level04/   # 3 → 4:   find a hidden file
├── level05/   # 4 → 5:   find the only human-readable file (file)
├── level06/   # 5 → 6:   find a file by size and properties (find)
├── level07/   # 6 → 7:   search the whole system by owner, group and size
├── level08/   # 7 → 8:   grep for a word in a large file
├── level09/   # 8 → 9:   find the only line that appears once (sort, uniq)
├── level10/   # 9 → 10:  extract readable strings from a binary (strings)
├── level11/   # 10 → 11: decode Base64
├── level12/   # 11 → 12: decode ROT13 (tr)
├── level13/   # 12 → 13: reverse a hexdump and decompress it repeatedly (xxd)
├── level14/   # 13 → 14: log in with an SSH private key
├── level15/   # 14 → 15: send data to a local port (netcat)
├── level16/   # 15 → 16: send data over TLS (openssl s_client)
├── level17/   # 16 → 17: scan a port range and find the TLS service (nmap)
├── level18/   # 17 → 18: compare two files (diff)
├── level19/   # 18 → 19: run a command over SSH when login is blocked
├── level20/   # 19 → 20: use a SetUID binary
├── level21/   # 20 → 21: answer a SetUID client with a netcat listener
├── level22/   # 21 → 22: read a cron job
├── level23/   # 22 → 23: work out a cron script that uses an MD5 hash
├── level24/   # 23 → 24: write a script for a cron job to run
├── level25/   # 24 → 25: brute-force a 4-digit PIN with a Bash loop
├── level26/   # 25 → 26: escape a restricted shell through the more pager
├── level27/   # 26 → 27: use a SetUID binary from the escaped shell
├── level28/   # 27 → 28: clone a git repo
├── level29/   # 28 → 29: recover data from git history (git log)
├── level30/   # 29 → 30: find data on another branch (git branch)
├── level31/   # 30 → 31: find data in a tag (git tag)
├── level32/   # 31 → 32: push a file past .gitignore
└── level33/   # 32 → 33: escape an uppercase shell with $0
```
