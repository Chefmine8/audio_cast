# Audio_cast (English Version)

## Introduction
This project aims to enable audio transfer from one device to another via PulseAudio or PipeWire (in development).

### Dependencies
- xdotool
- netcat
- cava
- fping

The mobile (in development, expected within the week) and lightweight ("allegee") versions do not have any dependencies except for PulseAudio or PipeWire.

---

### Client
- `start + ip`: Connects to a server.
- `start + ip + port`: Connects to a server with a different port.
- `stop`: Stops the connection to all servers.
- `mul + start`: Creates a link between all servers.
- `mul + stop`: Breaks the link between all servers.
- `auto + IP range` (e.g., 192.168.1.0): Automatically connects to all clients within an IP address range.

---

### Server
- `start`: Starts the server.
- `start + ip`: Starts the server while allowing connection from a specific IP only.
- `start + ip + port`: Starts the server while allowing connection from a specific IP and changing the communication port.
- `stop`: Stops the server.

---

### Power
- `down + auto + IP range` (e.g., 192.168.1.0): Shuts down all servers running within an IP address range.
- `down + ip`: Shuts down the server.

The mobile and lightweight ("allegee") versions do not support the following commands:

#### Client
- `auto + IP range`

#### Power
None are supported without netcat.

---

# Audio_cast

## Introduction
Ce projet a pour but de permettre le transfert d'audio d'un appareil à un autre via PulseAudio ou PipeWire (en développement).

### Dépendances
- xdotool
- netcat
- cava
- fping

Les versions mobiles (en développement, arrivée dans la semaine) et allégées ne comportent aucune dépendance, si ce n'est PulseAudio ou PipeWire.

---

### Client
- `start + ip` : Permet de se connecter à un serveur.
- `start + ip + port` : Permet de se connecter à un serveur avec un port différent.
- `stop` : Arrête la connexion à tous les serveurs.
- `mul + start` : Permet de créer le lien entre tous les serveurs.
- `mul + stop` : Permet de couper le lien entre tous les serveurs.
- `auto + la plage d'ip` (ex : 192.168.1.0) : Permet de se connecter automatiquement à tous les clients d'une plage d'adresses IP.

---

### Serveur
- `start` : Permet de démarrer le serveur.
- `start + ip` : Permet de démarrer le serveur en n'autorisant la connexion qu'à une IP précise.
- `start + ip + port` : Permet de démarrer le serveur en n'autorisant la connexion qu'à une IP précise et en changeant le port de communication.
- `stop` : Permet d'arrêter le serveur.

---

### Power
- `down + auto + plage d'ip` (ex : 192.168.1.0) : Permet d'éteindre tous les serveurs lancés sur une plage d'adresses IP.
- `down + ip` : Permet d'éteindre le serveur.

Les versions mobiles et allégées ne supportent pas les commandes suivantes :

#### Client
- `auto + la plage d'ip`

#### Power
Aucune n'est supportée en l'absence de netcat.

