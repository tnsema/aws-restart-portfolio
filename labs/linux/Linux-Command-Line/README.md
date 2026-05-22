# Linux Command Line Fundamentals

## Overview
This learning focused on the fundamentals of interacting with Linux through the command line. It covered the Linux login workflow, command syntax, basic terminal operations, and the concepts of standard input, standard output, and standard error.

Understanding these concepts is essential for Linux administration, cloud computing, DevOps, and cybersecurity.

---

## What I Learned

### 1. Linux Login Workflow

The Linux login workflow is the process that allows a user to securely access the operating system.

### Basic Login Process
1. The system starts and loads the Linux kernel.
2. Services and system processes initialize.
3. A login prompt or graphical login screen appears.
4. The user enters:
   - Username
   - Password
5. The system authenticates the credentials.
6. If successful:
   - A user session starts
   - The shell environment is loaded
   - User permissions are applied

### Important Concepts
- Authentication
- User accounts
- Permissions
- Shell sessions
- Home directories

---

## 2. Linux Command Syntax

Linux commands follow a structured format.

### General Syntax
```bash
command [options] [arguments]
```

### Example
```bash
ls -l /home
```

### Breakdown
- `ls` → command
- `-l` → option
- `/home` → argument

### Common Command Structure
| Part | Purpose |
|---|---|
| Command | Action to perform |
| Option | Modifies behavior |
| Argument | Target of the command |

---

## 3. Basic Command Line Operations

The command line allows users to interact directly with the operating system.

### Navigation Commands

#### Show Current Directory
```bash
pwd
```

#### List Files
```bash
ls
```

#### Change Directory
```bash
cd Documents
```

---

### File and Directory Operations

#### Create Directory
```bash
mkdir projects
```

#### Create File
```bash
touch notes.txt
```

#### Copy Files
```bash
cp file1.txt backup.txt
```

#### Move or Rename Files
```bash
mv old.txt new.txt
```

#### Remove Files
```bash
rm file.txt
```

---

### Viewing File Content

#### Display File Content
```bash
cat file.txt
```

#### View File Page by Page
```bash
less file.txt
```

---

## 4. Standard Input, Output, and Error

Linux programs communicate using streams.

### Standard Input (stdin)
- Used to provide input to a command
- Usually comes from the keyboard

Example:
```bash
cat
```

---

### Standard Output (stdout)
- Normal output produced by a command
- Displayed on the terminal by default

Example:
```bash
echo "Hello Linux"
```

---

### Standard Error (stderr)
- Displays error messages
- Separate from normal output

Example:
```bash
ls invalid-folder
```

---

## 5. Redirection Basics

Linux allows redirecting input and output.

### Redirect Output to File
```bash
echo "Linux" > file.txt
```

### Append Output
```bash
echo "More text" >> file.txt
```

### Redirect Errors
```bash
ls invalid-folder 2> errors.txt
```

---

## Skills Gained
- Understanding Linux login and authentication workflow
- Reading and writing Linux command syntax
- Navigating the Linux terminal
- Managing files and directories
- Understanding stdin, stdout, and stderr
- Using basic output redirection

---

## Why This Matters
The Linux command line is one of the most important skills in:
- Cloud Computing
- Cybersecurity
- DevOps
- System Administration
- Networking
- Software Development

Most servers and cloud systems are managed through the terminal, making command-line knowledge essential.

---

## Next Learning Goals
- Linux file permissions
- User and group management
- Bash scripting
- Linux process management
- Package management
- Networking commands
- Shell scripting automation

---

## Author
Thobile Sema

Learning Journey in:
- Linux
- Cloud Computing
- Networking
- Cybersecurity
