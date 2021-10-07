## Informations additionnelles

### Usage avec Nextcloud
1. Ouvrez votre fichier via webdav en utilisant https://linktoowncloud/remote.php/webdav/PATH-TO-YOUR-KDBX-FILE et votre nom d'utilisateur et votre mot de passe (pas besoin d'entrer votre nom d'utilisateur et votre mot de passe si vous utilisez un Keeweb privé, car il détectera automatiquement que vous êtes connecté dans Nextcloud)

### Usage pour Dropbox sync
1. [Créer](https://www.dropbox.com/developers/apps/create) une app Dropbox
2. Trouver votre clé d'application (dans la page Dropbox App, allez à Paramètres/Clé d'application)
3. Entrer la clé de l'application lorsque vous y êtes invité

### Ajouter des fichiers par défaut sur votre page d'accueil
1. Lisez https://github.com/keeweb/keeweb/wiki/Configuration#json-app-config
2. Dans votre config.json ajoutez l'entrée "files" avec les paramètres appropriés
