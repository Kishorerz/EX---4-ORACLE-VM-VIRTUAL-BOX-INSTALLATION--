Ex.3(A-C) Virtualization: Installation and configuration of Oracle VirtualBox & Kali Linux, and execution of Linux commands

Aim:
This focuses on setting up a virtualized environment using Oracle VirtualBox, followed by the installation of Kali Linux as a guest operating system. It also covers the execution of fundamental Linux commands, enabling learners to interact with the system via the command line interface. 
Procedure:
a.	Installation and configuration of Oracle VirtualBox on the host system
b.	Downloading and setting up Kali Linux within the virtual machine
c.	Execution of essential Linux commands 

3.a) Installation and configuration of Oracle VirtualBox

Aim: 
 To install and configure Oracle VM VirtualBox on your system.
Pre-requisites:
•	Access to a machine with internet connectivity.
•	Minimum of 4 GB RAM (recommended for running virtual machines smoothly).
•	Sufficient storage space to host virtual machines.
Steps:
1. Download Oracle VM VirtualBox:
Navigate to the Official Website:
o	Go to Oracle VM VirtualBox official website.
Download the installer:
o	On the homepage, click on Download VirtualBox.
o	Select the version for your operating system (Windows, macOS, Linux, Solaris).
o	For Windows, download the Windows Hosts executable.
o	For macOS, download the OS X Hosts file.
o	For Linux, download the relevant package for your distribution (Debian, Ubuntu, Fedora, etc.).
2. Install Oracle VM VirtualBox (Windows example):
Step 1: Launch Installer:
Double-click the downloaded installer file to begin.
The installer will prompt you to allow changes to your device; click Yes.
Step 2: VirtualBox Setup Wizard:
The VirtualBox Setup Wizard will open. Click Next to proceed.
Step 3: Select Installation Options:
Choose the default installation settings unless you need specific configurations.
Check or uncheck additional components such as networking features or shortcut creation.
Step 4: Network Interface Warning:
A prompt may inform you that the network connection will be temporarily interrupted during installation. Click Yes to proceed.
Step 5: Install VirtualBox:
Click Install to begin the installation.
Wait for the process to complete.
Step 6: Complete Installation:
Once the installation finishes, click Finish.
You will be prompted to launch VirtualBox after installation if the checkbox is checked.
3. Configure VirtualBox:
•	Launch Oracle VM VirtualBox:
o	Open the application from the start menu or desktop shortcut.
•	Create a Virtual Machine:
o	Click New to create a virtual machine.
o	Give the machine a name, choose the type (Linux, Windows, etc.), and the version of the operating system you want to install.
•	Allocate Resources:
o	Assign the virtual machine the required resources, including:
	Memory (RAM): Allocate at least 2 GB for Linux or 4 GB for Windows machines.
	Virtual Hard Disk: Create a new virtual hard disk or use an existing one. Recommended size is at least 20 GB.
•	Start Virtual Machine:
o	After creating the virtual machine, you will need to provide an ISO image of the operating system to install.
o	Click Start and then select your OS installer ISO.
o	Follow the prompts in the virtual machine to install the operating system.
Result :
Thus, the Oracle VM Virtual Box was installed successfully.

3.b) Installation and configuration of Kali Linux
Aim:

 To install and configure Kali Linux in Oracle VM VirtualBox.
Pre-requisites:
•	A system with Oracle VM VirtualBox installed.
•	At least 4 GB RAM and 20 GB free disk space.
•	Kali Linux ISO image, which can be downloaded from the official website.

Step-by-Step Installation Guide:
Step 1: Download Kali Linux ISO
1.	Go to the Kali Linux download page.
2.	Download the Kali Linux ISO file.
o	Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).
o	Download the Installer version for a full installation.

Step 2: Open Oracle VM VirtualBox
1.	Launch VirtualBox on your computer.

Step 3: Create a New Virtual Machine
1.	In VirtualBox, click on the New button to create a new virtual machine.
2.	Name and Type Settings:
o	Name: Give a name like "Kali Linux".
o	Type: Select Linux.
o	Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
3.	Click Next to proceed.

Step 4: Allocate Memory (RAM)
1.	Choose how much RAM to allocate to your virtual machine.
o	Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
2.	Click Next.

Step 5: Create a Virtual Hard Disk
1.	Select Create a virtual hard disk now.
2.	Click Create.

Step 6: Select Hard Disk File Type
1.	Choose VDI (VirtualBox Disk Image).
2.	Click Next.

Step 7: Storage on Physical Hard Disk
1.	Select Dynamically allocated (so the disk will grow as needed).
2.	Click Next.

Step 8: Allocate Storage Space
1.	Set the hard disk size. Kali Linux requires at least 20 GB of storage.
o	You can increase this if you plan to install many additional tools later.
2.	Click Create.

Step 9: Configure Kali Linux ISO
1.	Select the VM from the list in VirtualBox and click Settings.
2.	Navigate to Storage from the side menu.
3.	Under Controller: IDE, click the Empty CD icon.
4.	On the right, click the CD icon next to Optical Drive and choose Choose a disk file....
5.	Locate and select the Kali Linux ISO you downloaded.
6.	Click OK.

Step 10: Start the Virtual Machine
1.	In VirtualBox, click Start to boot up your Kali Linux virtual machine.

Step 11: Begin Kali Linux Installation
1.	The VM will now boot from the ISO. You’ll see a boot menu.
o	Select Graphical Install and press Enter.

Step 12: Select Language and Region
1.	Choose your language, location, and keyboard layout.
o	These can be configured to your preference.
2.	Click Continue after each selection.

Step 13: Configure the Network
1.	You’ll be prompted to configure the network.
o	Enter a hostname for your system (e.g., kali).
o	You can leave the domain name empty if you don’t need to set up a domain.

Step 14: Set Up Users and Passwords
1.	Create a root password for the administrator account.
o	Choose a strong password and re-enter it for confirmation.

Step 15: Partition Disks
1.	Choose Guided - use entire disk for simplicity (recommended for beginners).
2.	Select the virtual disk you created earlier.
3.	Choose All files in one partition.
4.	Finish partitioning and confirm to write the changes to disk.

Step 16: Install the System
1.	The installer will now copy files and install Kali Linux. This may take several minutes.

Step 17: Install GRUB Bootloader
1.	When prompted to install the GRUB bootloader, choose Yes.
2.	Select the virtual hard disk as the location to install GRUB.

Step 18: Complete Installation
1.	After the installation is complete, click Continue to reboot the virtual machine.

Step 19: Login to Kali Linux
1.	Once the machine reboots, you’ll be presented with a login screen.
2.	Log in using the root account and the password you set earlier.

Optional: Install Guest Additions
1.	Guest Additions enhance performance by providing better screen resolution and seamless mouse integration.
2.	To install them:
•	Go to Devices in the VirtualBox menu.
•	Select Insert Guest Additions CD Image and follow the installation steps inside Kali Linux.













Snap Shots:

 

Snapshot 1: Installing Oracle VirtualBox 

 
Snapshot 2: Adding Kali (Guest OS) on Oracle VirtualBox
 
Snapshot 3 :  Kali - The guest OS on Oracle Virtualbox
Result:
Thus, the guest OS Kali Linux was installed and configured successfully.

3.c) Linux commands execution in kali
Linux:
Linux is an open-source operating system. The kernel is the heart of Linux OS which helps the communication between hardware and software. The main advantage of Linux was the programmers can use Linux kernel to design their own custom OS.
     Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.

      Commands:

1.	ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls


2.	pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd



3.	mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


4.	rmdir Command
The rmdir command is used to delete a directory.	

Syntax: rmdir <directory name>



5.	cd Command
The cd command is used to change the current directory.

Syntax: cd <directory name>



6.	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 
7.	cp Command
The cp command is used to copya file or directory.

Syntax: cp <existing file name> <new file name>



8.	gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.
Syntax: gedit file_name

9.	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

10.	mv Command

The mv command is used to move a file or a directory form one location to another location.
Syntax: mv <file name> <directory path>

11.	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.
Syntax: rename 's/old-name/new-name/' files

12.	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

13.	tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

14.	id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

15.	grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

16.	tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

17.	chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)
Syntax: chmod<options><permissions><file_name>
18.	tar Command
The tar command is used for creating Archieve and extracting the archieve files.
Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
19.	chown Command
The chown command is used to change ownership.
Syntax: chown owner_name file_name

20.	make Command
The make command is used for building and maintaining group of program.
Syntax: make [-f makefile][options]…….[targets]….


21.	ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.
Syntax: ifconfig[options][interface]

22.	chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.
Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
23.	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.
Syntax: host <domain name> or <ip address>

24.	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

25.	sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


26.	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.
Syntax: cal

27.	clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

28.	mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


29.	df Command

The df command is used to display the disk space used in the file system. It displays theoutput as in the number ofused blocks, available blocks, and the mounted directory.
Syntax: df

30.	find Command
The find command is used to find a particular file within a directory.
Syntax: find.-name”*.pdf”















Result:
Thus, the various Linux commands were executed successfully in Kali guest OS.
