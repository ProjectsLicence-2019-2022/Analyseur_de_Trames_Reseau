## Introduction:
  Dans ce projet on se propose d'analyser des trames de données capturé avec un logiciel de capture  Wireshark. Dans ce contexte, la liste de données suivante sera présentée :
		- Ethernet 
		- IP  
		- UDP 
		- DNS 
		- DHCP 


## Structure du Programme:

 
- la classe  Verif  permet de charger le fichier qui contien la trame et vérifier sa consistance.


 - La méthode fic_to_liste charge le fichier et le sérialise sous frome d'une liste de valeur hexhadécimales
 - La methode ouverture de la classe verif permet de charger la trame au sein d'un ficher texte et d'assurer sa validité ainsi que de lui débrrasser les commentaire qui y figurent

-  La classe Ethernet  englobe l'ensemble des méthodes responsable de l'abalyse de la trame réseau.
-  La méthode  adresse_mac détermine les adresses Mac source et destination 
- la méthode trame_type  détermine le type et sa définition de la trame à partir d'un dictionnaire de types possibles"
- La classe IP renferme l'ensemble des méthodes responsables de déterminer     la version  l'IP, Tos , taille de données, l'identificateur , les flag , le TTL , le protocole utilisé , le checksum , l'IP source et destination ainsi que les options de la trame disponibles. 
