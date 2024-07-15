### Installation DHCP Linux 

## Étape 1 : Installation du serveur DHCP sur Ubuntu

Ouvrir un terminal et taper la commande "sudo apt install isc-dhcp-server"

 Une fois l'installation terminée, modifiez le fichier avec la commande "sudo nano /etc/default/isc-dhcp-server" pour définir les interfaces que DHCPD doit utiliser pour servir les demandes DHCPd.
 
<img width="725" alt="Capture d’écran 2024-07-15 à 10 06 13" src="https://github.com/user-attachments/assets/4c086216-b790-41aa-85e8-fc25aea3121c">

### Note : 
- Adresse statique : Une adresse IP statique est une adresse qui est fixée manuellement à un appareil par un administrateur réseau et ne change pas automatiquement.
- Adresse dynamique : Une adresse IP dynamique est une adresse attribuée automatiquement à un appareil par un serveur DHCP (Dynamic Host Configuration Protocol) et peut changer à chaque nouvelle connexion ou après un certain temps.
- Pour modifier le fichier de configuration des interfaces réseau sur un système basé sur Linux tapez "sudo nano /etc/network/interfaces

