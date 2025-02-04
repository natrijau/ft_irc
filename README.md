# ft_irc - Internet Relay Chat

ft_irc est un projet qui consiste à implémenter un serveur IRC en C++98. Ce serveur doit permettre aux clients IRC de se connecter et de communiquer en respectant le protocole IRC de base.

---

## Fonctionnalités

1. [Introduction au projet](#introduction-au-projet)
2. [Description des fonctionnalités](#description-des-fonctionnalités)
   - [Authentification](#authentification)
   - [Gestion des utilisateurs](#gestion-des-utilisateurs)
   - [Gestion des canaux](#gestion-des-canaux)
   - [Commandes IRC](#commandes-irc)
3. [Installation et utilisation](#installation-et-utilisation)
4. [Ressources utiles](#ressources-utiles)

---

## Description des fonctionnalités

### Authentification
- Connexion des utilisateurs avec mot de passe.

### Gestion des utilisateurs
- Ajout et suppression d'utilisateurs.
- Attribution de permissions.

### Gestion des canaux
- Création, suppression et administration des canaux.
- Gestion des modérateurs et opérateurs.

### Commandes IRC
- **KICK** : Expulser un utilisateur d'un canal.
- **INVITE** : Inviter un utilisateur dans un canal.
- **TOPIC** : Modifier ou afficher le sujet d'un canal.
- **MODE** : Gérer les modes d'un canal (restriction d'accès, opérateurs, etc.).

---

## Installation et utilisation

### Installation
1. Clonez le dépôt :
	```bash
	git clone <lien-du-depot>
	cd <dossier-du-depot>

2. Compilez le projet avec :
  	```bash
	make
	
3. Exécution : 
	```bash
	/ircserv <port> <password>
	port : Numéro du port d'écoute.
	password : Mot de passe de connexion au serveur.
	
4. Utilisez un client IRC comme WeeChat, irssi ou Netcat pour tester la connexion :
	```bash
	nc 127.0.0.1 6667

## Ressources utiles

- [Documentation officielle IRC](https://datatracker.ietf.org/doc/html/rfc1459)
- [Tutoriel sur l'utilisation d'IRC](https://wiki.mageia.org/en/Comment_utiliser_IRC-fr)
- [C++ FAQ](https://isocpp.org/faq)

