# 42_init
An introduction to Network and Systems Administration (DevOps)

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
  01 Get the list of the network interfaces of the machine without displaying any detail for these interfaces. Only the list of names.  
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
  01 Fichier où se trouve la version installée de Debian   
  02 Commande pour connaître le nom du système    
  XX Commande pour renommer le système    
  03 Fichier pour renommer le système de façon permanente    
  04 Commande pour savoir depuis combien de temps le système à été démarré    
  05 Commande qui détermine l’état du service SSH    
  06 Commande pour redémarrer le service SSH    
  07 Déterminer le PID du service SSHD    
  08 Fichier qui contient les clés RSA des machines autorisées à se connecter via SSH     
  09 Commande pour savoir quelles personnes sont connectées sur le système    
  10 Commande qui permet de lister les tables de partitions des disques    
  11 Commande permet d’afficher l’espace disponible et utilisé sur le système d’une manière humainement compréhensible    
  12 Déterminez la taille exacte de chaque dossier de /var d’une manière humainement compréhensible suivi du chemin de celui-ci    
  13 Commande qui permet, en temps réel, de trouver les processus en cours d’exécution   
  14 Lancez en background la commande tail -f /var/log/syslog    
  15 Commande qui permet de tuer le processus de la commande en background    
  16 Service qui permet de lancer des tâches à horaires régulières    
  17 Commande qui donne la liste des règles de pare-feu    
  18 Autoriser uniquement les IPs provenant de 10.0.0.0/8 (entrante) à se connecter au système    
  19 Interdire le reste des IP    
  XX Commande qui, en parallèle de la session graphique, permet de se connecter en ssh sur la machine     
  XX Commande qui permet d’arrêter le service ssh    
  XX Lister les services qui se lancent automatiquement lorsque la machine boot et indiquer le nom donné à ce type de service    
  XX Lister tous les utilisateurs existants sur la machine    
  XX Lister tous les utilisateurs réels de la machine    
  XX Commande qui permet d’ajouter un utilisateur local supplémentaire    
  XX Expliquez comment se connecter en tant que ce nouvelle utilisateur. (En session graphique et en session ssh)    
  XX Commande qui permet de lister tous les packages INSTALLÉS sur la machine    

### Scripts
  01 Réaliser un script qui affiche seulement le login, le UID et le Path de chaques entrée du fichier /etc/passwd   
  02 Réaliser un script qui met à jour l’ensemble des sources de package, puis de vos packages et qui log l’ensemble dans un fichier nommé /var/log/update_script.log  
  Créer une tâche planifiée pour ce script une fois par semaine à 4h00 du matin  
  03 Réaliser un script qui affiche la liste des fichiers triés par taille présents dans le dossier passé en argument  
  04 Réaliser un script qui permet de surveiller les modifications du fichier /etc/crontab et envoie un mail à ROOT si celui-ci a été modifié  
  Créez une tâche planifiée pour ce script tous les jours à minuit   
  05 Réaliser un script qui affiche 42  
  XX Réaliser un script qui permet de supprimer un user LOGUÉ sur la machine  
  XX Jamais 203  
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
