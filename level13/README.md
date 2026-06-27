# Bandit Level 12 → Level 13

### 🔑 Objective
Decompress a multi-layered file that has been repeatedly zipped, archived, and disguised using alternating tools like `gzip`, `bzip2`, and `tar`.

### 🛠️ Core Command Blueprint
```bash
# Example sequence: Reverse-compile hexdumps and extract recursive archives
xxd -r data.txt > compressed_blob
file compressed_blob
mv compressed_blob blob.gz && gunzip blob.gz
# Password: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
