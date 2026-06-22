# TP R204 – Téléphonie IP / VoIP

## Objectif du TP

L’objectif de ce TP était de découvrir une infrastructure de téléphonie IP professionnelle avec Cisco CallManager et Cisco Unity Connection.

Le travail portait sur :

* la configuration d’un environnement de téléphonie IP ;
* l’identification du rôle des serveurs CUCM et CUC ;
* la découverte d’un poste téléphonique Cisco ;
* l’analyse de l’adressage IP, du PoE, du DHCP et du VLAN voix ;
* la compréhension des différences entre une solution On-Premise et une solution SaaS.

## Travail réalisé

Dans ce TP, j’ai étudié le rôle des principaux composants d’une infrastructure VoIP.

Le serveur CUCM sert à gérer les appels, les téléphones IP, les utilisateurs, les numéros internes et le routage des appels.

Le serveur CUC sert principalement à gérer la messagerie vocale, les boîtes vocales et certains services vocaux automatisés.

J’ai aussi observé un téléphone IP Cisco. J’ai relevé plusieurs informations utiles comme son adresse IP, son adresse MAC, son modèle, son état et ses paramètres réseau.

## Points techniques compris

Un téléphone IP peut être alimenté de deux façons :

* avec un bloc d’alimentation externe ;
* avec le PoE, où l’alimentation passe directement par le câble Ethernet.

J’ai aussi compris qu’un téléphone IP peut être branché sur la même prise réseau qu’un PC tout en étant dans un réseau différent grâce au VLAN voix. Le trafic voix est séparé du trafic données, ce qui permet une meilleure organisation et une meilleure qualité de service.

## Lien avec la compétence Connecter

Ce TP est lié à la compétence **Connecter les entreprises et les usagers**, car il montre comment des utilisateurs peuvent être connectés à travers une infrastructure de téléphonie IP.

Il mobilise notamment :

* les postes téléphoniques IP ;
* le DHCP ;
* le VLAN voix ;
* les serveurs de communication ;
* la signalisation téléphonique ;
* la communication entre équipements réseau.

## Ce que j’ai appris

Ce TP m’a permis de comprendre que la téléphonie IP ne dépend pas seulement du téléphone. Elle repose sur plusieurs éléments : le serveur d’appel, la messagerie vocale, l’adressage IP, le VLAN voix, le DHCP et la configuration réseau.

J’ai aussi compris l’importance de documenter clairement une infrastructure pour pouvoir la configurer, la vérifier et la dépanner.
