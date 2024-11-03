# Guide d'Installation du Projet Symfony et Next.js avec Nginx

## Pré-requis

- Serveur Ubuntu/Debian
- Nginx
- PHP 7.4 ou supérieur
- Node.js (pour Next.js)
- OpenSSL pour HTTPS

### Étapes d'installation

1. **Configurer le Virtual Host avec HTTPS pour Nginx**  
   - Créez un fichier de configuration dans `/etc/nginx/sites-available/monsite.conf`
   - Activez la configuration et redémarrez Nginx

2. **Installer MariaDB et Créer la Base de Données**  
   - Installez MariaDB : `sudo apt install mariadb-server`
   - Configurez la base de données pour Symfony

3. **Installer phpMyAdmin**  
   - Installez phpMyAdmin et configurez-le avec Nginx

4. **Installation de Symfony**  
   - Clonez ou installez Symfony dans `/var/www/symfony`

5. **Installation du Projet Next.js**  
   - Créez le projet Next.js en local avec `npx create-next-app@latest`

---
