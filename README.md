# 🔐 Linux Password Reset Lab (Ubuntu)

## 📌 What This Project Shows

This lab shows how someone with physical access to a Linux machine can reset a user password using GRUB recovery mode.

It demonstrates why physical security is important.

## 🖥 Lab Setup
- Ubuntu (Virtual Machine)
- VirtualBox
- GRUB Bootloader

## 🛠 What I Did
- Rebooted the system
- Opened GRUB menu
- Entered recovery mode
- Dropped into root shell
- Remounted filesystem as writable
- Reset the user password
- Rebooted and logged in successfully

## 🖼 Screenshots

### 1️⃣ GRUB Recovery Menu
![GRUB Recovery](1.grub-recovery-menu.png)

### 2️⃣ Root Shell Option
![Root Shell Option](2-root-shell-options.png)

### 3️⃣ Root Terminal Access
![Root Terminal](3-root-terminal-access.png)

### 4️⃣ Password Reset Command
![Password Reset](4-password-reset-command.png)

### 5️⃣ Password Successfully Updated
![Password Success](5-password-success.png)

### 6️⃣ System Login Success
![System Login](6-system-login-success.png)


## 🔑 Key Commands Used
```bash
mount -o remount,rw /
ls /home
passwd username
reboot


