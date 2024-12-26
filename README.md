#Date 25-12-2024

**What is Unix?
**
  Unix is an operating system developed in 1969 by at bell labs.
  Unix is a multi-user,multi process operating system

**Unix Architecture**
User--
shell--Command interpreter and acts as an interface between user and kernel.It reads the user commands and interprets them as request to excute programe.Shell is also programming languagage.
kernel--kernel is set of layers ,the OS is commonly called Kernel,kernel consist of various subsystems likefile subsystem,device drivers,process subsystem,memory manager etc
Hardware

**Boot Process**
• The system BIOS checks the system and launches the first stage boot loader on the MBR of the primary hard disk.
• The first stage boot loader launches the second stage boot loader from the /boot/ partition.
• The kernel is loaded into memory, which in turn loads any necessary modules and mounts the root partition read-only.
• The kernel hands control of the boot process to the /sbin/init program
• The /sbin/init program loads all services and user-space tools, and mounts all partitions listed in /etc/fstab.
• The user is presented with a login prompt for the freshly booted Linux system
