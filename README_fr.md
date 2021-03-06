# Pinafor pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pinafor.svg)](https://dash.yunohost.org/appci/app/pinafor) ![](https://ci-apps.yunohost.org/ci/badges/pinafor.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pinafor.maintain.svg)  
[![Installer pinafor avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pinafor)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer pinafor rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Description rapide de cette application.

**Version incluse :** 1.20.0

## Captures d'écran

![](https://cdn.mastodon.technology/media_attachments/files/001/394/437/original/6589a6268c50b378.png)

## Démo

* [Démo officielle](Lien vers un site de démonstration de cette application.)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/pinafor%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/pinafor/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/pinafor%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/pinafor/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

**Plus d'informations sur la page de documentation :**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/pinafor_ynh/issues
 * Site de l'application : https://pinafore.social/
 * Dépôt de l'application principale : https://github.com/nolanlawson/pinafore
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pinafor -u https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing --debug
```
