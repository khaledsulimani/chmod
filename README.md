# Python Script Permission Example 🐍🔐

This repository demonstrates how to set permissions on a Python file using the chmod command.

## 📚 Overview

In this example, we have a Python script called task.py. The script needs specific permissions to be read, written, and executed by different users on a Linux-based system. The process of modifying file permissions using the chmod command will be shown.

## 🛠 Steps

1. *Creating the Example File*:
   We first create a directory called example and a Python script called task.py inside that directory.

2. *Setting Permissions*:
   To make the file accessible, we use the chmod command to change the permissions. The following commands are used:
   
   - **chmod 777 task.py**: This command grants read, write, and execute permissions to the owner, group, and others.
   - **chmod 755 task.py**: This command grants read, write, and execute permissions to the owner, and read and execute permissions to the group and others.

3. *Verifying Permissions*:
   Use the ls -l task.py command to verify the changes to the file permissions.

## 🔍 Example Commands

```bash
# Step 1: Create a new directory and change to it
mkdir example
cd example

# Step 2: Create a Python file
touch task.py

# Step 3: Set permissions using chmod
chmod 777 task.py

# Step 4: Verify the permissions
ls -l task.py

# Step 5: Change the permissions to 755
chmod 755 task.py
ls -l task.py 
```

---

## 📸 Project Results

### *chmod flowchart*:<img width="1799" height="1084" alt="image" src="https://github.com/user-attachments/assets/cf1d9e74-44a7-4725-af55-2705affd8a86" />

### *chmod flowchart*:![صورة واتساب بتاريخ 1447-01-27 في 19 06 39_c551461a](https://github.com/user-attachments/assets/00e59560-183b-41d2-89cb-54b2cbd7e84e)


---

## 🧑‍💻 Author
- **khaled mahmoud sulaimani** – [@khaledsulimani](https://github.com/khaledsulimani)

---
