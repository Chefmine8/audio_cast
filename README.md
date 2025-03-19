# Audio_cast  
Ce projet a pour but de permettre le transfert d'audio d'un appareil à un autre via PulseAudio ou PipeWire (en développement).  

### Dépendances :  
- xdotool  
- netcat  
- cava  
- fping  

Les versions mobiles (en développement arrivé dans la semaine) et allégées ne comportent aucune dépendance, si ce n'est PulseAudio ou PipeWire.

---

### Client :  
- `start + ip` : Permet de se connecter à un serveur.  
- `start + ip + port` : Permet de se connecter à un serveur avec un port différent.  
- `stop` : Arrête la connexion à tous les serveurs.  
- `mul + start` : Permet de créer le lien entre tous les serveurs.  
- `mul + stop` : Permet de couper le lien entre tous les serveurs.  
- `auto + la plage d'ip` (ex : 192.168.1.0) : Permet de se connecter automatiquement à tous les clients d'une plage d'adresses IP.  

---

### Serveur :  
- `start` : Permet de démarrer le serveur.  
- `start + ip` : Permet de démarrer le serveur en n'autorisant la connexion qu'à une IP précise.  
- `start + ip + port` : Permet de démarrer le serveur en n'autorisant la connexion qu'à une IP précise et en changeant le port de communication.  
- `stop` : Permet d'arrêter le serveur.  

---

### Power :  
- `down + auto + plage d'ip` (ex : 192.168.1.0) : Permet d'éteindre tous les serveurs lancés sur une plage d'adresses IP.  
- `down + ip` : Permet d'éteindre le serveur.  

---

Les versions mobiles et allégées ne support pas les commandes suivantes :

### Client :
- `auto + la plage d'ip`

### Power : 
Aucune n'est supporté en l'absence de netcat
