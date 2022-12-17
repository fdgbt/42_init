# 42_init
An introduction to Networks and Systems Administration  

# Expected Result
All the commands used in this project are uploaded in this repository.  
They are sorted in 3 domains, following the subject: Network, System, Scripts.

# Special Doc
A unique document has been created for this project.  
In this rare document you can find the subject with a reminder for all notions learned, but also explanations for each script.  
It has been designed to be very complete in terms of informations, and represents dozens of hours of research and writing.  
It takes the form of a tutorial of 75 pages, allowing you to be guided step by step and to complete the project from A to Z.  
It can be shared upon request.  

I would like to thanks a lot the 42 peers (and friends) who helped me to produce this document: Hugo D., Julia A. and Julien B.  
Unfortunately only French is available for now, the content is organised as below:

### Thanks
### Versions of document
### Summary

### Introduction
  Check the operation (status) of a service  
  Help with the “service” command  
  List all installed services  
  Enable a service  
  Disable a service  
  Reset a service (stop then restart)  

### Packages Manager
  Install a package  
  Delete a package  
  Delete a package with all its dependencies  
  Also delete all config files (purge)  
  Delete all installer packages     
  Update all packages   
  Update a specific package  

### Terminal commands usefull to the sys-admin and networks
  Basic commands  
  System commands  
  Network commands  
  Configuration files  

### Comment

### Make scripts executable

### Install a VM at 42 (Mac OS X)
  Install VirtualBox  
  Install a VM in VirtualBox  
  Install Debian in the VM  
  What to do once Debian is installed  
  VM storage  
  
### Network
  01 Get the list of the network interfaces of the machine without displaying any detail for these interfaces (only the list of names)  
  02 Identify the IP address of the Ethernet interface  
  XX Display only the IP address of the Ethernet interface  
  XX Display the Broadcast address of the Ethernet interface  
  XX Display all the IP addresses that are part of the same subnet  
  03 Identify the MAC address of the Wi-Fi card  
  04 Identifiy the default gateway in the routing table  
  05 Identify the IP address of the DNS that responds to the following url: slash16.org   
  06 Get the complete path of the file that contains the IP address of the DNS server you’re using  
  07 Query an external DNS server on the slash16.org domain name (ie. : google 8.8.8.8)  
  08 Identify the host provider for the Slash16 website  
  09 Identify the public IP address of 42.fr   
  10 Identify the network devices between your computer and the slash16.org domain  
  11 Use the output of the previous command to find the name and IP address of the device that makes the link between you (local network) and the outside world  
  12 Check that the server with the 10.51.1.253 IP address is reachable from your computer  
  XX Identify the server type for 10.51.1.253 IP address  
  XX Identify the IP address assigned to you by the DHCP server  
  13 Use the reverse DNS to find out the name of the server linked to the 10.51.1.81 IP address  
  XX With the result of the previous question and the reverse DNS, find the name of your host  
  14 What file contains the local DNS entries  
  15 Make the 46.19.122.85 address reroute to intra.42.fr  

### System  
  01 In what file can you find the installed version of your Debian  
  02 What command can you use to rename your system  
  03 What file has to be modified to make it permanent  
  04 What command gives you the time since your system was last booted  
  05 Name the command that determines the state of the SSH service  
  06 Name the command that reboots the SSH service  
  07 Figure out the PID of the SSHD service  
  08 What file contains the RSA keys that are authorized to connect via SSH  
  09 What command lets you know who is connected to the System  
  10 Name the command that lists the partition tables of external devices  
  11 Name the command that displays the available space left on the system  
  12 Figure out the exact size of each folder of /var  
  13 Name the command that find currently running processes  
  14 Run the "tail -f /var/log/syslog" command in background  
  15 Find the command that kills the background command’s process  
  16 Find the service which makes it possible to run specific tasks following a regular schedule  
  17 Find the command which gives the list of firewall rules  
  18 With the previous command, authorize only IP addresses from 10.0.0.0/8 to connect to your system  
  19 With the previous command, forbid all others IP  
  XX Command which, in parallel with the graphical session, allows you to connect to the machine with SSH  
  XX Command to stop the SSH service  
  XX List the services that start automatically when the machine boots and give the name of this type of service  
  XX List all existing users on the machine  
  XX List all real users of the machine  
  XX Command to add a new local user  
  XX Explain how to log in as this new user (in graphical session and in ssh session)  
  XX Command that lists all the packages INSTALLED on the machine  

### Scripts
  01 Write a script which displays only the login, UID and Path of each entry of the /etc/passwd file  
  02 Write a script which updates all the package sources, then all the packages, and then logs everything in a file named /var/log/update_script.log  
     Create a scheduled task for this script, once per week at 4 AM  
  03 Write a script which displays the list of files from the folder given as parameter, sorted by size  
  04 Write a script which monitors the modifications made to the /etc/crontab file and sends an e-mail to root if the file is modified  
     Create a scheduled task to run this script everyday at midnight  
  05 Write a script which displays 42  
  XX Write a script that allows you to delete a LOGGED user on the machine  
  XX Never two without three  
  XX Start a new 42 project  

### Annexes

### Conclusion

# 2019 Update
There is a new version of the subject and some adjustment has been made with the objectives (02 03 etc).  
Objectives marqued as 'XX' are from new subject and also explained completely in the document.  
The updated document, including old and new objectives, is available in French and can be shared upon request.

# Keywords
System & Network Administration  
Unix  
DevOps
