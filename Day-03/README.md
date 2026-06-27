# Cloud Engineering - Day 3

## Topics Learned
- IP Address
- Public & Private IP
- Ports
- VPC (Virtual Private Cloud)
- Subnets
- Internet Gateway (IGW)
- Security Groups
- AWS EC2 Basics
- Amazon S3 Basics

---

## Networking Basics

### IP Address
- Every computer connected to a network has an IP address.
- Public IP → Accessible from the internet.
- Private IP → Used only inside a private network.
- EC2 instances use a Public IP for SSH access.

### Ports
Common ports:

| Service | Port |
|---------|------|
| SSH | 22 |
| HTTP | 80 |
| HTTPS | 443 |

---

## AWS Networking

### VPC (Virtual Private Cloud)
- A private network inside AWS.
- Used to securely host cloud resources.

### Subnet
- A smaller network inside a VPC.
- Public subnet → Internet access.
- Private subnet → No direct internet access.

### Internet Gateway (IGW)
- Connects a VPC to the internet.
- Required for internet connectivity.

### Security Group
- Works as a virtual firewall.
- Controls inbound and outbound traffic.
- Example:
  - Allow SSH → Port 22
  - Allow HTTP → Port 80

---

## AWS EC2

EC2 (Elastic Compute Cloud)
- Virtual server in AWS.
- Used to host websites and applications.
- Supports Linux and Windows servers.
- SSH (Port 22) is used to connect to Linux EC2 instances.

---

## Amazon S3

- S3 stands for **Simple Storage Service**.
- Used for cloud storage.
- Stores files securely over the internet.

---

## Key Takeaways

- Learned networking fundamentals.
- Understood IP addresses and ports.
- Learned VPC, Subnet, Internet Gateway, and Security Groups.
- Explored AWS EC2 and Amazon S3 basics.

---

## Screenshot

Add your **Day-3 notes image** below.

![Day 3 Notes](day3-notes.png)
