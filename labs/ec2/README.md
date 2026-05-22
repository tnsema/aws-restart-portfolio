# Amazon EC2 Fundamentals

## Overview
This learning focused on Amazon EC2 (Elastic Compute Cloud), one of the core AWS services used to launch and manage virtual servers in the cloud.

The training covered navigating the AWS Management Console, creating EC2 instances, selecting instance types, configuring networking and storage, connecting to Linux servers, and understanding the main components involved in deploying cloud infrastructure.

This was an important step in understanding cloud computing and real-world server deployment.

---

# What I Learned

## 1. What Amazon EC2 Is

Amazon EC2 (Elastic Compute Cloud) is an AWS service that allows users to create and manage virtual servers in the cloud.

EC2 provides scalable computing capacity without needing to buy or manage physical hardware.

### Common Uses of EC2
- Hosting web applications
- Running Linux servers
- Backend APIs
- Databases
- Cloud labs and testing
- DevOps environments
- Security testing environments

---

# 2. Navigating the AWS Management Console

I learned how to navigate the AWS Console and access EC2 services.

### Areas Explored
- AWS Dashboard
- EC2 Dashboard
- Running Instances
- Instance Launch Wizard
- Security Groups
- Key Pairs
- Volumes
- Elastic IPs
- Monitoring Section

### Skills Gained
- Navigating AWS regions
- Understanding resource organization
- Managing cloud resources from the console

---

# 3. Creating an EC2 Instance

I learned the step-by-step process of launching an EC2 virtual server.

## Instance Creation Workflow

### Step 1 — Choose an Amazon Machine Image (AMI)
An AMI is a template used to create an instance.

Examples:
- Ubuntu
- Amazon Linux
- Debian
- Red Hat Enterprise Linux

### Step 2 — Choose an Instance Type
I learned how AWS provides different instance types depending on workload requirements.

Examples:
- `t2.micro`
- `t3.micro`
- `m5.large`

### Instance Categories
| Type | Purpose |
|---|---|
| General Purpose | Balanced workloads |
| Compute Optimized | High CPU performance |
| Memory Optimized | High memory workloads |
| Storage Optimized | Fast storage access |

---

# 4. Configuring Instance Settings

I learned how to configure the environment before launching the instance.

### Configurations Included
- Network selection
- Subnet configuration
- Auto-assign public IP
- Firewall rules
- Storage allocation
- User data scripts

---

# 5. Understanding Key Pairs

AWS uses key pairs for secure SSH authentication.

### What I Learned
- Public and private key concepts
- Downloading `.pem` key files
- Securing private keys
- Using SSH for remote access

### Example SSH Connection
```bash
ssh -i mykey.pem ubuntu@server-ip
```

---

# 6. Security Groups

Security Groups act as virtual firewalls for EC2 instances.

## Rules Configured
- SSH (Port 22)
- HTTP (Port 80)
- HTTPS (Port 443)

### Skills Gained
- Allowing and restricting traffic
- Understanding inbound and outbound rules
- Improving server security

---

# 7. Connecting to a Linux EC2 Instance

I learned how to connect to Linux servers hosted on AWS.

### Methods Used
- SSH
- EC2 Connect
- Terminal access

### Linux Commands Practiced
```bash
pwd
ls
cd
mkdir
sudo
```

---

# 8. Understanding EC2 Storage

I learned about storage options attached to EC2 instances.

## Elastic Block Store (EBS)
EBS provides persistent storage for EC2 instances.

### Concepts Learned
- Root volumes
- Volume sizing
- Persistent storage
- Attaching and detaching volumes

---

# 9. Starting, Stopping, and Terminating Instances

I learned the lifecycle management of EC2 instances.

### Instance States
- Running
- Stopped
- Rebooting
- Terminated

### Important Understanding
- Stopping preserves storage
- Termination permanently removes the instance

---

# 10. Monitoring and Scaling Concepts

I explored how AWS monitors EC2 instances.

### Topics Covered
- CloudWatch monitoring
- CPU utilization
- Memory usage concepts
- Instance scaling basics
- Availability and reliability

---

# 11. Networking Basics in EC2

I learned foundational networking concepts used with EC2.

### Concepts Explored
- Public IP addresses
- Private IP addresses
- Virtual Private Cloud (VPC)
- Subnets
- Internet access
- Security isolation

---

# Skills Gained
- Navigating the AWS Console
- Launching EC2 instances
- Choosing appropriate instance types
- Configuring Linux cloud servers
- Understanding cloud networking basics
- Using SSH for remote server access
- Managing EC2 storage and security
- Understanding cloud infrastructure fundamentals

---

# Why EC2 Matters

Amazon EC2 is one of the most widely used cloud services in the industry.

EC2 knowledge is important for:
- Cloud Computing
- DevOps
- Cybersecurity
- Linux Administration
- Backend Development
- Infrastructure Engineering

Many modern applications and enterprise systems run on EC2 or similar cloud virtual machines.

---

# Next Learning Goals
- Load Balancers
- Auto Scaling
- IAM Roles and Permissions
- S3 Integration
- CloudWatch Monitoring
- Linux Server Administration
- Nginx and Apache Deployment
- Docker on EC2
- VPC Deep Dive
- Infrastructure Automation

---

# Author
Thobile Sema

Learning Journey in:
- AWS Cloud Computing
- Linux
- Networking
- Cybersecurity
- Cloud Security
