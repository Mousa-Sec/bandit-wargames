# Bandit Level 8 → Level 9

### 🔑 Objective
Isolate the only singular line of text string inside a configuration text dump that appears once without duplicates.

### 🛠️ Core Command Blueprint
```bash
# Arrange text rows sequentially to filter out repeating groups
sort data.txt | uniq -u
# Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
