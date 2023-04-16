# LaRuche
Objectifs 
La ruche a été proposé afin de tenter de répondre à la problématique de la difficulté d'accès à la culture dans certaines zones rurales disposant de peu de cinémas, bibliothèques, musées, évènements culturels... 
Prenant la forme d'une boîte à lire numérique (et aussi inspiré de ce concept),
la ruche a pour objectif de favoriser le partage de contenus numériques en dehors de la sphère d'Internet, afin de prendre place dans l'espace public.
Ce projet se veut en faveur d'une culture pour tous et accessible à tous.

Fonctionnement
La ruche est un point d’accès Wi-Fi public ainsi qu’un serveur de fichiers, contrôlés par un Raspberry Pi. 
Celui-ci est contenu dans ce boîter, alimenté par une batterie externe et relié à un interrupteur.
C'est via un logiciel FTP (File Transfert Protocol) que vous pouvez récupérer ou déposer des fichiers sur le serveur.
Le Raspberry Pi prend aussi le rôle d’un serveur DHCP (Dynamic Host Configuration Protocol) et via le point d’accès Wi-Fi qu'il génère, il s’occupe de distribuer les adresse IP, ce qui forme un réseau local.

Contexte
La ruche a été réalisé dans le cadre du projet de diplôme de Rebecca Ramon, pour l'obtention de la licence Design à l'Université de Nîmes. 
