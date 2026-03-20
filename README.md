#  Linux Basic CLI – Practice Notes

This repository contains my hands-on learning of basic Linux command-line operations.

---

##  Understanding the Terminal Prompt

Example:

```
cybrary@linux:~/Desktop$
```

* cybrary → user
* linux → hostname
* ~/Desktop → current directory

---

##  Basic Commands

### Check user

```
whoami
```

### Check hostname

```
hostname
```

### Show directory

```
pwd
```

---

##  Navigation

```
cd ..
ls
ls -l
ls -la
```

---

##  File Operations

### Create folder

```
mkdir labwork
```

### Enter folder

```
cd labwork
```

### Create files

```
touch file1.txt file2.txt file3.txt
```

---

##  Write to file

```
echo "This is file 1" >> file1.txt
cat file1.txt
```

---

##  Manage files

```
cp file1.txt blue/
mv file2.txt green/
rm -i file1.txt
```

---

##  Search

```
find . -name "*.txt"
grep -r "This"
```

---

##  Pipes

```
cat unsorted | sort
cat unsorted | sort | uniq
cat unsorted | wc -w
```

---

##  What I Learned

* Linux commands basics
* File navigation
* File management
* Searching files
* Using pipes
