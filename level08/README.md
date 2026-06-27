# Bandit Level 7 → Level 8

### 🔑 Objective
Isolate a password nested inside a massive dictionary text pile (`data.txt`) sitting immediately adjacent to the text label `millionth`.

### 🛠️ Core Command Blueprint
```bash
# Pipe file logs directly into a search string filter
cat data.txt | grep "millionth"
# Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
