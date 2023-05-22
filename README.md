<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# phpIPAM for YunoHost

[![Integration level](https://dash.yunohost.org/integration/phpipam.svg)](https://dash.yunohost.org/appci/app/phpipam) ![Working status](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![Install phpIPAM with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install phpIPAM quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

phpIPAM is an open-source web IP address management application. Its goal is to provide light and simple IP address management application. It is ajax-based using jQuery libraries, it uses php scripts and javascript and some HTML5/CSS3 features, so some modern browser is preferred to be able to display javascript quickly and correctly.

**Shipped version:** 1.5.2~ynh1

**Demo:** http://demo.phpipam.net

## Screenshots

![Screenshot of phpIPAM](./doc/screenshots/dashboard.png)

## Documentation and resources

* Official app website: <https://phpipam.net>
* Official admin documentation: <https://phpipam.net/documents/>
* Upstream app code repository: <https://github.com/phpipam/phpipam>
* YunoHost documentation for this app: <https://yunohost.org/app_phpipam>
* Report a bug: <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
or
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
