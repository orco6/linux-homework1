# Linux Homework: Directory and File Operations

## Commands Used

### 1. Creating Directories
```bash
mkdir -p ~/homework/{dir1,dir2,dir3}

### 2. Creating files
```bash
touch ~/homework/dir1/{file1.txt,file2.txt,file3.txt}

### 3. Adding content to files
```bash
echo "hey file1" > file1.txt
echo "hey file2 how are you?" > file2.txt
echo "hey file3 sup?" > file3.txt

### 4. Searching text in files using grep
```bash
grep "hey" ~/homework/dir1/*.txt

### 5. Finding files modified in the last 7 days
```bash
find ~/homework/dir1 -type f -mtime -7

In the directory, there is a screenshot with all the commands and the output
