# 42_init
An introduction to Network and Systems Administration (DevOps)

# Expected Result
All the commands used in this project are uploaded in this repository.  
They are sorted in 3 domains: Network, System, Scripts.

# Special Doc
A unique document has been created for this project.  
In this rare document you can find the subject and a reminder for all notions learned, but also explanations for each script.  
It has been designed to be very complete in terms of informations, and represents dozens of hours of research and writing.  
It takes the form of a tutorial of 75 pages, allowing you to be guided step by step and to complete the project from A to Z.  
It can be shared individually upon request.  

I would like to thanks a lot the 42 peers (and friends) who helped me to produce this document: Hugo D., Julia A. and Julien B.  
Unfortunately only French is available for now, the content is organised as below:

## Table des matières

### Remerciements
### Versions du document
### Table des matières

### Introduction
  Vérifier le fonctionnement (status) d’un service  
  Aide concernant la commande “service”  
  Lister tous les services installés  
  Activer un service  
  Désactiver un service  
  Réinitialiser un service (stop puis start)  

### Gestionnaire de paquets
  Installer un paquet [package]  
  Supprimer un paquet  
  Supprimer un paquet avec toutes ses dépendances logicielles  
  Supprimer également les fichiers de config (purge)  
  Supprimer tous les paquets d’installation   
  Mettre à jour tous les paquets   
  Mettre à jour un paquet en particulier  

### Commandes Terminal utiles à l’admin. systèmes & réseaux
  Les commandes basiques   
  Les commandes systèmes   
  Les commandes réseaux   
  Les fichiers de configurations  

### Remarque

### Rendre script exécutable

### Installer une VM à 42 (Mac OS X)
  Installer VirtualBox  
  Installer une VM dans VirtualBox  
  Installer Debian dans la VM  
  A faire une fois Debian installé  
  Stockage de la VM  
  
### Network
  01 Afficher juste les noms de la liste des interfaces réseaux  
  02 Afficher les caractéristiques d’une interface réseau spécifique (ex: Ethernet)  
  XX Afficher juste l’adresse IP de l’interface Ethernet  
  XX Afficher l’adresse de Broadcast de l’interface Ethernet  
  XX Afficher toutes les adresses IP qui font partie du même sous-réseau  
  03 Afficher juste l’adresse MAC de la carte Wi-Fi  
  04 Afficher la gateway par défaut dans la table de routage  
  05 Afficher l’IP du serveur DNS qui répond sur le domaine suivant : slash16.org  
  06 Récupérer le path complet du fichier dans lequel est écrit l’adresse IP du serveur DNS que l’on utilise  
  07 Interroger un serveur DNS externe sur le nom de domaine slash16.org (ex : google 8.8.8.8)  
  08 Trouver chez quel hébergeur est le site de Slash16   
  09 Trouver l’IP Publique de 42.fr   
  10 Afficher les différents appareils réseaux entre votre poste et le domaine slash16.org   
  11 Trouvez grâce au résultat de la commande précédente le nom et l’IP du matériel qui fait le lien entre vous (réseau local) et l’extérieur  
  12 Vérifiez que le serveur avec l’adresse IP 10.51.1.253 est touchable depuis votre poste   
  XX Déterminer le type de serveur 10.51.1.253   
  XX Trouvez l’IP qui vous a été assignée par le serveur dhcp   
  13 Vérifiez grâce au Reverse DNS le nom du serveur correspondant à l’IP 10.51.1.81   
  XX Grâce à la question précédente et au reverse DNS, retrouvez le nom de votre host   
  14 Quel est le fichier contenant les entrées locales DNS   
  15 Faites pointer intra.42.fr sur l’adresse suivante 46.19.122.85   

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
  XX Réaliser un script qui permet de supprimer un user LOGUÉ sur la machine   
  XX Jamais 203  
  02 Réaliser un script qui met à jour l’ensemble des sources de package, puis de vos packages et qui log l’ensemble dans un fichier nommé /var/log/update_script.log. Créer une tâche planifiée pour ce script une fois par semaine à 4h00 du matin   
  03 Réaliser un script qui affiche la liste des fichiers triés par taille présents dans le dossier passé en argument  
  04 Réaliser un script qui permet de surveiller les modifications du fichier /etc/crontab et envoie un mail à ROOT si celui-ci a été modifié. Créez une tâche planifiée pour ce script tous les jours à minuit   
  05 Réaliser un script qui affiche 42    
  XX Start a new 42 project    
  XX Script maison pour tester son Lem-in    

### Annexes

### Conclusion

# 2019 Update
There is a new version of the subject and some adjustment has been made with the objectives (02 03 etc).  
Objectives marqued as 'XX' are from new subject and also explained completely in the document.  
The updated document, including old and new objectives, can be shared individually upon request.
