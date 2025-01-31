# Linux-File-Listing-Project

![Image](https://github.com/user-attachments/assets/244f2e3a-ae2e-4289-8a5b-afcb7b9caa94)

This project teaches you how to create a custom `ls` command that shows directory sizes in a user-friendly way. I also provide instructions for installing Ubuntu, a recommended Linux distribution, to help new users transition smoothly. The guide includes screenshots, proper command formats, and explanations of each command's function and options. The focus is on the pre-implementation stage, offering an overview of common commands to ensure an easy setup for new Linux systems.

**Installation of the software**

This guide will explain the installation process for Ubuntu using VMware Workstation. This guide will focus on providing detailed instructions for the server installation process. Follow these steps for proper installation of the Ubuntu Operating System from VMWARE:

1.	Visit the website www.vmware.com and create an account with your company email address and personal credentials. The IT department will then provide you with a license key.
2.	After logging into the VMware account, create another account on the www.broadcom.com account with the same company email address and personal credentials. 
3.	Click the dropdown next to your name on www.broadcom.com and click VMware Cloud Foundation. 
4.	Click on "My Downloads," scroll down to VMware Workstation Pro, and select version 17.5.2 for personal use. On the following page, click on HTTPS Download. 
5.	After the download is complete, open its VMware-workstation-full-17.5.2-23775571.exe file. Enter the license key given by your IT department.
6.	Please visit https://ubuntu.com/download/desktop to download the latest version of the Ubuntu Desktop ISO. Choose the correct architecture (32-bit or 64-bit) for your system (2024 Canonical Ltd., n.d.). Download Ubuntu 24.04 LTS for desktop PCs and laptops.
7.	Open VMware Workstation. Click on "File" in the menu and select "New Virtual Machine." The New Virtual Machine Wizard will open. Choose "Typical" and click "Next."
8.	To begin the installation, select the "Installer disc image file (iso)" option, then browse and choose the Ubuntu ISO file. Finally, click "Next" to proceed.
9.	When setting up your virtual machine, remember to name it, choose a storage location, specify a minimum disk capacity of 25 GB, and select the option to store the virtual disk as a single file. Click "Next" to proceed.
10.	Feel free to modify hardware settings such as processors, memory allocation, and other configurations to suit your system's capabilities.
11.	Review your settings, click 'Finish,' and consider additional configurations before starting the virtual machine.
12.	Set the boot sequence to start from the Ubuntu ISO file. You can just follow the on-screen instructions to begin the Ubuntu installation process.
13.	During Ubuntu installation, follow prompts for language, keyboard layout, and disk partitioning. After installation, restart the virtual machine to complete the process.
14.	After installing Ubuntu, install VMware Tools for enhanced performance and integration. Access the VMware Workstation menu, select "VM," then "Install VMware Tools," and follow the on-screen instructions

**Demonstrate command-line operations that will provide the following information**

a)	A listing of files in the directory and common file attributes.

Command: ls –all

![Image](https://github.com/user-attachments/assets/dc1f1c3e-5f17-471c-b484-7aa726dd7172)

b)	The current directory (hint:  also known as the present working directory).

Command: pwd command

![Image](https://github.com/user-attachments/assets/1af9ea2d-df9a-48ac-9f69-3e1f413759eb)

c)	Create a file, then copy it to a different directory.

Command: ls

Command: touch rudell.file.txt

Command: cp rudell_file.txt rudell_file1.txt

![Image](https://github.com/user-attachments/assets/7a7f8769-db94-45cd-bec2-d1369807aef2)

d)	Create a second file and move it to a different directory.

![Image](https://github.com/user-attachments/assets/6d45aade-37b7-4023-95de-7a330411d37c)

e)	Remove the first file and the copy you created.

Command: rm rudell_file.txt

![Image](https://github.com/user-attachments/assets/c7f5f4b6-aba0-4bf7-83ae-67a34239dea5)

Command: unlink rudell_file1.txt

![Image](https://github.com/user-attachments/assets/96e48db2-308c-4ff6-a5bb-8745112ef4ed)

f)	The manual page for a given command.

Command: man cp

![Image](https://github.com/user-attachments/assets/5d75aa15-1f84-4011-9b2f-dc89f5434e75)

g)	Create a text file, then use an editor to modify the content.  Then display the content of the modified file.

![Image](https://github.com/user-attachments/assets/e6497bb4-da08-4014-a587-aa64d4292ac1)

![Image](https://github.com/user-attachments/assets/cf419b2f-73a5-4243-b2d6-660659326cc2)

h)	Show running processes on the system.  

Command: ps

Command: ps -A

![Image](https://github.com/user-attachments/assets/3283fdde-2f25-4d8f-b53b-3e7efaa36362)

i)	Demonstrate how to search for a specific process.

Command: ps -C firefox

![Image](https://github.com/user-attachments/assets/cf50272f-89b2-4ada-b360-cb1f80bebdcf)

j)	Forcibly stop a running process.

Command: kill 8523

![Image](https://github.com/user-attachments/assets/61efcf3c-f128-4eae-a189-52f125e9d835)

![Image](https://github.com/user-attachments/assets/850c23aa-8334-46d5-a95e-3fa3011148b9)

k) On the final screenshot, you need to open a command line and type in the following commands (without the quotes):

Command: date

Command: echo CMIT391

Command: echo <your name here> (Replace your name here with your name)

![Image](https://github.com/user-attachments/assets/7bae8442-68bc-4f7d-8545-ae3746045e7a)



























