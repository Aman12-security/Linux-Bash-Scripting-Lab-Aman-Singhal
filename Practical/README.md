# Linux Practical Assignment – Set B (Even Roll Numbers)

> **Student:** Aman Singhal
> **Roll No:** 2301410004

---

## Question 1: Directory Operations

Create a main directory named `YourName_RollNo` and perform the following operations:

### Steps

```bash
# Create main directory
mkdir AmanSinghal_2301410004
cd AmanSinghal_2301410004

# a) Create subdirectories
mkdir Lab1, Lab2, Lab3

# b) Move Lab3 inside Lab1
mv Lab3 Lab1/

# c) Create file inside Lab2
touch Lab2/studentinfo.txt

# d) Copy studentinfo.txt into Lab1
cp Lab2/studentinfo.txt Lab1/

# e) Show directory tree structure
tree
```

### Expected Tree Output

```
.
├── Lab1
│   └── studentinfo.txt
├── Lab1,
├── Lab2,
│   └── studentinfo.txt
└── studentinfo.txt

4 directories, 3 files
```

---

## Question 2: Shell Script Writing

Create a shell script named `scriptB_RollNo.sh` that:

- Accepts two numbers from the user
- Displays addition, subtraction, multiplication
- Displays the greater number

### Script: `scriptB_2301410004.sh`

```bash
#!/bin/bash

echo "6"
read num1

echo "4"
read num2

echo "Addintion: $((num1 + num2))"
echo "Subtraction: $((num1 - num2))"
echo "Multiplication: $((num1 * num2))"

if [$num1 -gt $num2]
then
    echo "$num2 is greater"
else
    echo "Both number are equal"
fi
```

### Run the Script

```bash
chmod +x scriptB_2301410004.sh
./scriptB_2301410004.sh
```

### Sample Output

```
6
12
4
2
Addintion: 14
Subtraction: 10
Multiplication: 24
```

---

## Question 3: Search & Filters

Create a file `names_RollNo.txt` with 5 names and perform the following operations:

### Sample File: `name_rollno.txt`

```
Aman_2301410004
Shanki_2301410027
Aryan_2301410018
Adhvay_2301410002
```

### Commands & Output

```bash
# a) Sort names alphabetically
sort name_rollno.txt
```
```
Adhvay_2301410002
Aman_2301410004
Aryan_2301410018
Shanki_2301410027
```

```bash
# b) Search names containing letter 'a'
grep "a" name_rollno.txt
grep -i "a" name_rollno.txt   # case-insensitive
```
```
Aman_2301410004
Shanki_2301410027
Aryan_2301410018
Adhvay_2301410002
```

```bash
# c) Count number of lines
wc -l name_rollno.txt
```
```
4 name_rollno.txt
```

```bash
# d) Display first 3 lines
head -n 3 name_rollno.txt
```
```
Aman_2301410004
Shanki_2301410027
Aryan_2301410018
```

```bash
# e) Display last 2 lines
tail -n 2 name_rollno.txt
```
```
Aryan_2301410018
Adhvay_2301410002
```

---

## Commands Reference

| Command | Description |
|---------|-------------|
| `mkdir` | Create a directory |
| `cd` | Change directory |
| `mv` | Move file or directory |
| `cp` | Copy file |
| `touch` | Create an empty file |
| `tree` | Display directory tree |
| `ls -R` | List files recursively |
| `sort` | Sort file contents |
| `grep` | Search for a pattern |
| `wc -l` | Count lines |
| `head -n` | Display first N lines |
| `tail -n` | Display last N lines |
