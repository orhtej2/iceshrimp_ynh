<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Iceshrimp for YunoHost

[![Integration level](https://dash.yunohost.org/integration/iceshrimp.svg)](https://dash.yunohost.org/appci/app/iceshrimp) ![Working status](https://ci-apps.yunohost.org/ci/badges/iceshrimp.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/iceshrimp.maintain.svg)

[![Install Iceshrimp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=iceshrimp)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Iceshrimp quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Iceshrimp is a decentralized and federated social networking service, implementing the ActivityPub standard.

It was forked from Calckey Firefish (itself a fork of Misskey) in mid-2023, to focus on stability, performance and usability instead of new features.

**Shipped version:** v2023~ynh1

**Demo:** https://demo.example.com

## Screenshots

![Screenshot of Iceshrimp](./doc/screenshots/example.jpg)

## Documentation and resources

* Official app website: <https://iceshrimp.dev>
* Upstream app code repository: <https://iceshrimp.dev/iceshrimp/iceshrimp>
* YunoHost Store: <https://apps.yunohost.org/app/iceshrimp>
* Report a bug: <https://github.com/YunoHost-Apps/iceshrimp_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
or
sudo yunohost app upgrade iceshrimp -u https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
