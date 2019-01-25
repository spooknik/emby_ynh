# Jellyfin app for YunoHost
## Overview
Jellyfin is a fork of Emby media server that has no premium licenses or features, and no hidden agendas.

- [Yunohost project](https://yunohost.org)
- [Jellyfin website](https://jellyfin.github.io/)

![](https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/branding/SVG/banner-logo-solid.svg?sanitize=true)

**Shipped version:** 10.0.1

### Installing guide:

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/spooknik/jellyfin_ynh
 1. Admin username is : **root**.
 
 2. You **must install the app to /emby** otherwise it will not work. This is a [hardcoded limitation](https://github.com/jellyfin/jellyfin/issues/337) for Jellyfin.

 
### Upgrade this package:

        $ sudo yunohost app upgrade embyserver -u https://github.com/spooknik/jellyfin_ynh

