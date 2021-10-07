# Keeweb pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb) ![](https://ci-apps.yunohost.org/ci/badges/keeweb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/keeweb.maintain.svg)  
[![Installer Keeweb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=keeweb)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Keeweb rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Client Web pour la lecture et l'édition de fichiers Keepass en local. Il peut également synchroniser avec WebDAV (Nextcloud, Dropbox, Google Drive, OneDrive...)


**Version incluse :** 1.18.7~ynh1

**Démo :** https://app.keeweb.info/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

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

## Documentations et ressources

* Site officiel de l'app : https://keeweb.info/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://github.com/keeweb/keeweb/wiki
* Dépôt de code officiel de l'app : https://some.forge.com/example/example
* Documentation YunoHost pour cette app : https://yunohost.org/app_keeweb
* Signaler un bug : https://github.com/YunoHost-Apps/keeweb_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps