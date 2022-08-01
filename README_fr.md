<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Grocy pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/grocy.svg)](https://dash.yunohost.org/appci/app/grocy) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/grocy.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/grocy.maintain.svg)  
[![Installer Grocy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grocy)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Grocy rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

grocy is a web-based self-hosted groceries & household management solution for your home.

**Version incluse :** 3.3.1~ynh1

**Démo :** https://en.demo.grocy.info/stockoverview

## Captures d'écran

![Capture d'écran de Grocy](./doc/screenshots/stock-en.png)

## Avertissements / informations importantes

## Configuration

Connexion par défaut
```
	utilisateur : admin
	mot de passe : admin
```

## Limitations

:warning: Pour l'instant, Grocy doit être installé dans un domaine racine ou un sous-domaine.

## Documentations et ressources

* Site officiel de l'app : <https://grocy.info/>
* Dépôt de code officiel de l'app : <https://github.com/grocy/grocy>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_grocy>
* Signaler un bug : <https://github.com/YunoHost-Apps/grocy_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/grocy_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade grocy -u https://github.com/YunoHost-Apps/grocy_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>