# Cloud Engineering - Day 4

## Topics Learned
- AWS EC2
- Amazon Machine Image (AMI)
- Instance Types
- Key Pair (.pem)
- Security Groups
- Elastic Block Store (EBS)
- EC2 Instance Launch
- Running & Stopping Instances

---

## Practical Work

### AWS EC2 Instance Creation
- Logged in to AWS Management Console.
- Opened the EC2 Dashboard.
- Created a new EC2 instance.
- Selected **Amazon Linux 2023 AMI**.
- Chose **t3.micro** (Free Tier eligible).
- Generated an RSA Key Pair (.pem).
- Configured Security Group to allow SSH (Port 22).
- Launched the EC2 instance successfully.
- Verified the instance status as **Running**.
- Stopped the instance to avoid unnecessary charges.

---

## AWS Concepts

### EC2 (Elastic Compute Cloud)
- Virtual server provided by AWS.
- Used to host applications and websites.

### AMI (Amazon Machine Image)
- Template used to create EC2 instances.
- Contains the operating system and required software.

### Instance Type
- Defines CPU, RAM, and performance.
- **t3.micro** is Free Tier eligible.

### Key Pair
- Used for secure SSH login.
- Downloaded as a `.pem` file.
- Required to connect to the EC2 instance.

### Security Group
- Acts as a virtual firewall.
- Controls inbound and outbound traffic.
- Allowed SSH access on Port 22.

### EBS (Elastic Block Store)
- Persistent storage attached to EC2 instances.
- Stores operating system and user data.

---

## Key Takeaways

- Learned how to create an EC2 instance.
- Understood the purpose of AMI, Key Pair, Security Group, and EBS.
- Gained hands-on experience with AWS EC2.
- Learned the importance of stopping instances to manage cloud costs.

---

## Screenshot

Add your Day 4 notes image below.

![Day 4 Notes](day4-notes.png)
