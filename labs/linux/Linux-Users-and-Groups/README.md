# Linux User Management and AWS IAM Fundamentals

## Overview
This learning focused on managing users and groups in Linux, understanding permission elevation using `su` and `sudo`, and learning the fundamentals of AWS Identity and Access Management (IAM).

These concepts are essential in Linux administration, cloud computing, cybersecurity, and infrastructure management because they control authentication, authorization, and system security.

---

# What I Learned

# 1. Managing User Accounts in Linux

I learned how Linux handles user accounts and authentication.

## User Account Concepts
Each user in Linux has:
- A username
- A password
- A home directory
- User permissions
- A unique user ID (UID)

---

## Common User Management Commands

### Create a User
```bash
sudo useradd username
```

### Create User with Home Directory
```bash
sudo useradd -m username
```

### Set User Password
```bash
sudo passwd username
```

### Delete a User
```bash
sudo userdel username
```

### View Current User
```bash
whoami
```

---

# 2. Managing Group Accounts

Linux groups are used to organize users and manage permissions more efficiently.

## What I Learned
- Users can belong to multiple groups
- Groups simplify permission management
- Group membership controls access to files and resources

---

## Common Group Commands

### Create a Group
```bash
sudo groupadd developers
```

### Add User to Group
```bash
sudo usermod -aG developers username
```

### View User Groups
```bash
groups username
```

### Delete a Group
```bash
sudo groupdel developers
```

---

# 3. Understanding Linux Permissions

Linux uses permissions to control access to files and system resources.

## Permission Types
| Permission | Meaning |
|---|---|
| Read (r) | View file contents |
| Write (w) | Modify files |
| Execute (x) | Run files/programs |

---

## Permission Categories
- Owner
- Group
- Others

### View Permissions
```bash
ls -l
```

---

# 4. Using `su` and `sudo`

I learned how Linux allows privilege escalation for administrative tasks.

---

## The `su` Command

The `su` command switches from one user account to another.

### Example
```bash
su root
```

### What I Learned
- Requires the target user's password
- Commonly used to switch to the root account

---

## The `sudo` Command

The `sudo` command allows users to execute commands with elevated privileges.

### Example
```bash
sudo apt update
```

### What I Learned
- Provides temporary administrator access
- Safer than always using the root account
- Helps improve system security and accountability

---

# 5. Root User and Privilege Management

The root user has full control over the Linux system.

## Important Understanding
- Root access should be limited
- Incorrect commands can damage the system
- Least privilege principle improves security

---

# 6. AWS Identity and Access Management (IAM)

I learned how AWS manages authentication and authorization using IAM.

IAM is the service AWS uses to securely control access to AWS resources.

---

# 7. IAM Core Concepts

## IAM Users
Represents an individual identity in AWS.

### Example Uses
- Administrator accounts
- Developers
- Cloud engineers

---

## IAM Groups
Groups are collections of users with shared permissions.

### Example
- Developers Group
- Administrators Group
- Security Team Group

---

## IAM Policies
Policies define what actions are allowed or denied.

### Example Permissions
- Launch EC2 instances
- Access S3 buckets
- Manage IAM users

---

## IAM Roles
Roles provide temporary permissions to AWS services or users.

### Common Examples
- EC2 accessing S3
- Lambda functions accessing DynamoDB

---

# 8. Authentication and Authorization in AWS

## Authentication
Verifies identity.

Example:
- Username and password
- Access keys
- Multi-factor authentication (MFA)

---

## Authorization
Determines what actions are allowed.

Example:
- Permission to create EC2 instances
- Permission to read S3 objects

---

# 9. Security Best Practices Learned

## Linux Security
- Avoid logging in directly as root
- Use `sudo` instead of root where possible
- Limit unnecessary permissions

---

## AWS IAM Security
- Follow least privilege principles
- Use IAM roles instead of sharing credentials
- Enable MFA
- Avoid using the AWS root account daily

---

# Skills Gained
- Creating and managing Linux users
- Managing Linux groups
- Understanding Linux file permissions
- Using `su` and `sudo`
- Understanding privilege escalation
- Understanding AWS IAM fundamentals
- Managing authentication and authorization concepts
- Learning cloud security best practices

---

# Why This Matters

User and permission management are critical in:
- Cloud Computing
- Cybersecurity
- Linux Administration
- DevOps
- Infrastructure Engineering

Strong identity and access management reduces security risks and protects systems from unauthorized access.

---

# Next Learning Goals
- Advanced Linux permissions
- File ownership and ACLs
- IAM policy creation
- IAM roles in EC2
- Multi-factor authentication (MFA)
- Linux security hardening
- Cloud security fundamentals

---

# Author
Thobile Sema

Learning Journey in:
- Linux
- AWS Cloud Computing
- Networking
- Cybersecurity
- Cloud Security
