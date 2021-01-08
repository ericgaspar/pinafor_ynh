# Pinafor for YunoHost

[![Integration level](https://dash.yunohost.org/integration/pinafor.svg)](https://dash.yunohost.org/appci/app/pinafor) ![](https://ci-apps.yunohost.org/ci/badges/pinafor.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pinafor.maintain.svg)  
[![Install Pinafor with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pinafor)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Pinafor quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
An alternative web client for Mastodon, focused on speed and simplicity.

**Shipped version:** 1.20.0

## Screenshots

![](https://cdn.mastodon.technology/media_attachments/files/001/394/437/original/6589a6268c50b378.png)

## Demo

* [Official demo](https://pinafore.social/)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/pinafor%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/pinafor/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/pinafor%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/pinafor/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/pinafor_ynh/issues
 * App website: https://pinafore.social/
 * Upstream app repository: https://github.com/nolanlawson/pinafore
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing --debug
or
sudo yunohost app upgrade pinafor -u https://github.com/YunoHost-Apps/pinafor_ynh/tree/testing --debug
```
