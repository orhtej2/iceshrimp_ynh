<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Iceshrimp pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/iceshrimp.svg)](https://dash.yunohost.org/appci/app/iceshrimp) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/iceshrimp.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/iceshrimp.maintain.svg)

[![Installer Iceshrimp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=iceshrimp)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Iceshrimp rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Iceshrimp est un service de réseau social décentralisé et fédéré, implémentant le standard ActivityPub.

Il a été forké de Calckey et Firefish (lui-même forké de Misskey) à la mi-2023, afin de se concentrer sur la stabilité, les performances et la facilité d'utilisation plutôt que sur de nouvelles fonctionnalités.

**Version incluse :** 2023.12.5~ynh1

## Captures d’écran

![Capture d’écran de Iceshrimp](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://iceshrimp.dev>
- Dépôt de code officiel de l’app : <https://iceshrimp.dev/iceshrimp/iceshrimp>
- YunoHost Store : <https://apps.yunohost.org/app/iceshrimp>
- Signaler un bug : <https://github.com/YunoHost-Apps/iceshrimp_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade iceshrimp -u https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
