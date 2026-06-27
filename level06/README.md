# Bandit Level 5 → Level 6

### 🔑 Objective
Scrape nested directory structures recursively to extract a specific non-executable file that is exactly 1033 bytes in footprint size.

### 🛠️ Core Command Blueprint
```bash
# Query directories for specific size constraints and execution flags
find . -type f -size 1033c ! -executable
# Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
