<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Hat.sh voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![Hat.sh met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Hat.sh snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Hat.sh is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.


**Geleverde versie:** 2.3.6~ynh4

**Demo:** <https://hat.sh>

## Schermafdrukken

![Schermafdrukken van Hat.sh](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <hat.sh>
- Officiele beheerdersdocumentatie: <https://hat.sh/about/>
- Upstream app codedepot: <https://github.com/sh-dv/hat.sh>
- YunoHost-store: <https://apps.yunohost.org/app/hat>
- Meld een bug: <https://github.com/YunoHost-Apps/hat_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/hat_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
of
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
