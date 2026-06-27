# Cloud Engineering - Day 2

## Topics Learned
- Linux users and identity
- Sudo command
- Linux file permissions
- chmod permissions
- SSH basics
- Cloud basics (AWS)

---

## Commands Practiced

```bash
whoami
id
sudo apt update
ls -l
chmod 644 linux-basics.txt
chmod 777 linux-basics.txt
```

---

## What I Learned

### 1. Users & Identity
- `whoami` → Shows current user.
- `id` → Shows user ID and group ID.
- AWS IAM is used to manage users and permissions.

### 2. Sudo
- `sudo` gives temporary administrator access.
- Used for system-level tasks.

### 3. Linux File Permissions
Permission symbols:
- `r` = Read
- `w` = Write
- `x` = Execute

Example:

```
-rw-r--r--
```

Owner → Read & Write

Group → Read

Others → Read

### 4. chmod Numbers

| Number | Permission |
|---------|------------|
| 7 | rwx |
| 6 | rw- |
| 4 | r-- |

Examples:

```bash
chmod 644 linux-basics.txt
chmod 777 linux-basics.txt
```

### 5. SSH
- SSH allows secure remote login to a server.
- Default SSH port is **22**.

---

## Key Takeaways

- Learned Linux users and permissions.
- Understood `sudo` command.
- Practiced `chmod` permission changes.
- Learned SSH basics.
- Built stronger Linux fundamentals for Cloud Engineering.

---

## Screenshot

Add your **Day-2 notes image** below.

![Day 2 Notes](day2-notes.png)
