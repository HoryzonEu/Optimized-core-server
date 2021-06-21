# Optimized-server-core

Bienvenue sur le projet du serveur de Horyzon.

## Contribution
Vos contributions sont les bienvenues et doivent être approuvées par un administrateur. Si celle-ci est validée, elle est alors fusionné au projet et effective sur le serveur lors de son redémarrage quotidien.

## Obfuscation
Certaines données sont sensibles et ont donc été soit supprimé (plugins payants), soit obfusqué (identifiants BDD, Token).
Cependant tous les fichiers de configuration restent disponible à la modification et les variables obfusquées sont désobfusquées sur notre serveur en sécurité.

## Variables

### Propriétés serveur
Pour les identifiants des propriétés du serveur, veuillez utiliser les variables suivantes :
```bash
Server name: '$server_name_'
Server address: '$server_address_'
Server port: '$server_port_'
Query port: '$query_port_'
RCON port: '$rcon_port_'
RCON password: '$rcon_password_'
```

### Base de donnée
Il est préférable de favoriser l'utilisation de MySQL ou MariaDB lorsqu'il l'est possible.
Pour les informations de connexion, veuillez utiliser les variables suivantes :
```bash
Host: '$mysql_host'
Port: '$mysql_port'
```

Pour les identifiants de connexion pour les données spécifiques au serveur Hub, veuillez utiliser les variables suivantes :
```bash
User: '$mysql_user_'
Password: '$mysql_password_'
Database: '$mysql_database_'
```

Pour les identifiants de connexion pour les données communes à différents serveurs, veuillez utiliser les variables suivantes :
```bash
User: '$mysql_user_proxy'
Password: '$mysql_password_proxy'
Database: '$mysql_database_proxy'
```

### Bot Discord
Pour les identifiants du Bot Discord Horyzon, veuillez utiliser les variables suivantes :
```bash
Invite: '$discord_invite'
General channel: '$discord_channel_general'
Console channel: '$discord_channel_console'
Token: '$discord_token'
```