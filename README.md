# Modèle d'application pour Yunohost

- [Projet Yunohost](https://yunohost.org)
- [Exemple de site web d'application](https://example.com)

Description de l'application.

## Usage
- Copie cette application avant de travailler dessus.
- Edite le fichier `conf/nginx.conf` pour correspondre aux prérequis.
- Edite le fichier `manifest.json` avec les informations relatives à ton application
- Edite les scripts `install`, `upgrade`, `remove`, `backup`, et `restore`.
- Rajoute un fichier `LICENSE` dans le paquet de l'application.
- Edite `README.md`.

**Plus d'information sur la page de la documentation:**    
https://yunohost.org/packaging_apps

**Mise à jour de ce paquet:**  
`sudo yunohost app upgrade --verbose example -u https://github.com/YunoHost-Apps/example_ynh`

**Multi-user:** Yes/No. How about the ldap and HTTP auth support.
