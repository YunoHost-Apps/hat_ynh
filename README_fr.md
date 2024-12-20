<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Hat.sh pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![Installer Hat.sh avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Hat.sh rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Hat.sh est une application Web qui fournit un chiffrement local sécurisé des fichiers dans le navigateur. Il est rapide, sécurisé et utilise des algorithmes cryptographiques modernes avec un chiffrement/déchiffrement de flux AEAD fragmenté.

**Version incluse :** 2.3.6~ynh4

**Démo :** <https://hat.sh>

## Captures d’écran

![Capture d’écran de Hat.sh](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <hat.sh>
- Documentation officielle de l’admin : <https://hat.sh/about/>
- Dépôt de code officiel de l’app : <https://github.com/sh-dv/hat.sh>
- YunoHost Store : <https://apps.yunohost.org/app/hat>
- Signaler un bug : <https://github.com/YunoHost-Apps/hat_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/hat_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
