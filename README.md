## Ex.3(A-C) Virtualization: Installation and configuration of Oracle VirtualBox & Kali Linux, and execution of Linux commands

### Aim:
This focuses on setting up a virtualized environment using Oracle VirtualBox, followed by the installation of Kali Linux as a guest operating system. It also covers the execution of fundamental Linux commands, enabling learners to interact with the system via the command line interface.

---

## 3.a) Installation and configuration of Oracle VirtualBox

### Aim:
To install and configure Oracle VM VirtualBox on your system.

### Pre-requisites:
- Access to a machine with internet connectivity.
- Minimum of 4 GB RAM (recommended for running virtual machines smoothly).
- Sufficient storage space to host virtual machines.

### Steps:

1. **Download Oracle VM VirtualBox:**
   - Navigate to the [official website](https://www.virtualbox.org).
   - Click on "Download VirtualBox".
   - Select the version for your OS (Windows, macOS, Linux, Solaris).

2. **Install Oracle VM VirtualBox (Windows example):**
   - Launch the installer and allow device changes.
   - Follow the VirtualBox Setup Wizard (Click Next).
   - Choose default installation settings.
   - Confirm network interface changes.
   - Click "Install" and then "Finish".

3. **Configure VirtualBox:**
   - Launch VirtualBox and click `New`.
   - Enter a name, OS type, and version.
   - Allocate resources (2GB+ RAM, 20GB+ disk).
   - Attach ISO and install the OS in the virtual environment.

### Result:
Thus, the Oracle VM Virtual Box was installed successfully.

---

## 3.b) Installation and configuration of Kali Linux

### Aim:
To install and configure Kali Linux in Oracle VM VirtualBox.

### Pre-requisites:
- Oracle VM VirtualBox installed
- 4 GB RAM and 20 GB free disk
- Kali Linux ISO (download from official website)

### Steps:
1. Download Kali Linux ISO (32/64 bit as per system).
2. Launch VirtualBox and create a new VM.
3. Set type: Linux, Version: Debian (64-bit).
4. Allocate memory: 2 GB or more.
5. Create a dynamically allocated virtual hard disk (at least 20 GB).
6. Attach ISO via Settings > Storage > Controller: IDE.
7. Start VM and select "Graphical Install".
8. Follow setup: language, network, user/password, partitioning.
9. Install system and GRUB bootloader.
10. Reboot and log in with root credentials.
11. *(Optional)* Install Guest Additions via Devices > Insert Guest Additions CD Image.

### Result:
Thus, the guest OS Kali Linux was installed and configured successfully.

---

## 3.c) Linux commands execution in Kali

### Linux:
Linux is an open-source operating system. The kernel is the heart of Linux OS which helps communication between hardware and software.

### Common Commands:

- `ls` - List directory contents  
- `pwd` - Print working directory  
- `mkdir <dir>` - Create directory  
- `rmdir <dir>` - Remove directory  
- `cd <dir>` - Change directory  
- `cat <file>` - View or create file  
- `cp file1 file2` - Copy file  
- `mv file dir/` - Move file  
- `rename 's/old/new/' files` - Rename files  
- `head file` / `tail file` - Show first/last 10 lines  
- `id` - Show user ID info  
- `grep 'text' file` - Search content  
- `chmod 777 file` - Full access  
- `chown user file` - Change ownership  
- `make` - Build software  
- `ifconfig` - Network interface config  
- `host domain` - DNS lookup  
- `gzip file` - Compress file  
- `sort file` - Alphabetically sort  
- `cal` - Calendar  
- `clear` - Clear terminal  
- `mail -s "Subject" user@example.com` - Send mail  
- `df` - Show disk usage  
- `find . -name "*.pdf"` - Find PDF files

### Result:
Thus, the various Linux commands were executed successfully in Kali guest OS.
