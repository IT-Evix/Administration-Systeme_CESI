##Contexte :  

Depuis peu l’entreprise remarque des usurpations d’identité lors de connexions sur le réseau.  

##Problématique : 

Comment mettre en place une solution d’identification sécurisée dans notre LAN ? 

Comment permettre aux commerciaux d’avoir un accès à distance aux éléments souhaités de manière sécurisée ?  

Comment éviter qu’un MiM puisse intercepter les données ?  

  

##Contraintes : 

Des personnes externes au site doivent pouvoir se connecter à distance  

La connexion passe par un serveur d’annuaire  

Attention à la sécurité -> la solution doit être robuste  

##Mots clefs : 

Synchronisation immédiate : La synchronisation est une manipulation qui vous permet d'accéder aux mêmes informations d'un support à un autre. C'est une copie rapide de vos données sur un appareil afin de 
pouvoir les consulter facilement. 

Key logger : logiciel ou programme qui enregistre toute action faite depuis le clavier d'un utilisateur et transmet ces informations à un attaquant

MiM : Dans le contexte du prosit, un MiM ou MITM signifie Man In The Middle, il s'agit d'une attaque informatique sur le réseau utilisant généralement des requêtes arp pour redirriger le trafic réseau d'un 
utilisateur ou d'un serveur vers le système attaquant. 

SSO : L'authentification unique, souvent désignée par le sigle anglais SSO est une méthode permettant à un utilisateur d'accéder à plusieurs applications informatiques en ne procédant qu'à une seule 
authentification

Frame IP : https://www.frameip.com/

Extranet : L'extranet est une extension du système d'information de l'entreprise. Il s'appuie sur un réseau de télécommunication relié à internet permettant à toutes entreprises de partager des documents 
ou des informations privées à leurs salariés, filiales, clients, fournisseurs ou prestataires.

TLS : TLS (Transport Layer Security) est le successeur du protocole à SSL. TLS (Transport Layer Security) est une nouvelle version de SSL. Cela fonctionne plus ou moins comme le SSL, utilisant le chiffrement 
pour protéger le transfert des données et de l'information. 

SSL :SSL signifie couche des sockets sécurisés (secure sockets layer). Protocole pour navigateurs Web et serveurs qui permet l'authentification, le chiffrement et le déchiffrement des données envoyées sur 
l'Internet. 

PKI :L'infrastructure de gestion de clés ou Public Key Infrastructure (PKI) délivre des certificats numériques permettant d'effectuer des opérations de cryptographie. Ces derniers sont utilisés pour la 
vérification et l'authentification de la validité des différentes parties impliquées dans un échange électronique. 

PPTP : PPTP (Point-to-point tunneling protocol - RFC 2637), protocole de tunnel point-à-point, est un protocole d'encapsulation PPP sur IP conçu par Microsoft. Il permet de mettre en place des réseaux privés
virtuels (VPN) au-dessus d'un réseau public. 

VPN : Un VPN (Virtual Private Network) est un type de réseau informatique qui permet la création de liens directs entre des ordinateurs distants. Côté fonctionnement, le VPN repose sur la création d'un 
tunnel (via un protocole d'encapsulation) entre les deux ordinateurs 

L2TP: Layer 2 Tunneling Protocol (L2TP) signifie protocole de tunnellisation de niveau 2. L2TP est un protocole réseau utilisé pour créer des Virtual Private Networks (VPN), le plus souvent entre un 
opérateur de collecte de trafic (dégroupeur ADSL ou opérateur (Le mot opérateur est employé dans les domaines) de téléphonie. 

OpenVPN : OpenVPN est un VPN, ou private virtual network, il sécurise les accès distants aux applications d'entreprise, en créant un réseau privé virtuel. 

IKEv2 : Internet Key Exchange version 2 (IKEv2) est un protocole de tunnelisation basé sur IPsec qui fournit un canal de communication VPN sécurisé entre les équipements VPN pairs et définit la négociation 
et l'authentification des associations de sécurité IPsec de manière protégée.

CERT devoteam : Devoteam est référencé en tant que CERT depuis 2007, ce qui signifie que ses équipes sont en mesure de fournir des prestations de réponse aux incidents, de veille et de recherches. 

RSA : RSA est un système cryptographique, ou cryptosystème, pour le chiffrement à clé publique. Il est souvent utilisé pour la sécurisation des données confidentielles, en particulier lorsqu'elles sont 
transmises sur un réseau peu sûr comme Internet.

Certificat x509 : 509 est une norme spécifiant les formats pour les certificats à clé publique, les listes de révocation de certificat, les attributs de certificat, et un algorithme de validation du chemin 
de certification, définie par l'Union internationale des télécommunications (UIT).


DevenSys : https://www.devensys.com/
 

Kerberos : Protocole d'authentification basé sur l'échange de tickets, conçu pour permettre l'authentification mutuelle au travers de réseaux non sécurisés.

Cerbère : cringe 

 
##Livrables :  

Procédure de mise en place les solutions pour l’authentification à distance pour l’administrateur 

Procédure de mise en place les solutions pour l’authentification à distance pour les utilisateurs  

##Pistes de solution :  

On pourrait utiliser un serveur VPN (Emilien) 

Utiliser pfsense (Edwin) 

Mettre en place un PKI dans le SI, un certificat par user ? par poste de travail ? les deux ? (Antoine) 

Faire un VPN avec packet tracer (Antoine) 

##Plan d’action :  

Deux solutions à voir simultanément : sécurité réseau interne et extérieur  

Définir les mots clefs 

Mettre en place un VPN depuis PfSense  

Ecrire les procédures user et administrateur  

Script d’automatisation  

Aider Roger  

Limiter les connections au serveur  

##Généralisation : 

VPN  

Sécurité des mot de passe 

Protocoles sécurisés 


##Résolution



