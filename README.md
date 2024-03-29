<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Librarian for YunoHost

[![Integration level](https://dash.yunohost.org/integration/librarian.svg)](https://dash.yunohost.org/appci/app/librarian) ![Working status](https://ci-apps.yunohost.org/ci/badges/librarian.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/librarian.maintain.svg)

[![Install Librarian with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=librarian)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Librarian quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

An alternative frontend for LBRY/Odysee. Inspired by Invidious and Libreddit.

### Features

- Lightweight
- JavaScript not required*
- No ads
- No tracking
- No crypto garbage


**Shipped version:** 2022.05.14~ynh2

**Demo:** https://lbry.bcow.xyz/@RetroMusic:d/1987-Rick-Astley-Never-Gonna-Give-You-Up-1920x1080:f

## Screenshots

![Screenshot of Librarian](./doc/screenshots/screeshot.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: Librarian has been discontinued. See: https://bcow.xyz/posts/archiving-librarian/

## Documentation and resources

* Official app website: <https://lbry.bcow.xyz/>
* Official admin documentation: <https://codeberg.org/librarian/librarian/wiki>
* Upstream app code repository: <https://codeberg.org/librarian/librarian>
* YunoHost Store: <https://apps.yunohost.org/app/librarian>
* Report a bug: <https://github.com/YunoHost-Apps/librarian_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/librarian_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/librarian_ynh/tree/testing --debug
or
sudo yunohost app upgrade librarian -u https://github.com/YunoHost-Apps/librarian_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>