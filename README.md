# ZanY's Home Assistant add-on repository

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fzanyraspi%2Fhome-assistant-addons)

If you want to do add the repository manually, please follow the procedure highlighted in the [Home Assistant website](https://home-assistant.io/hassio/installing_third_party_addons). Use the following URL to add this repository: https://github.com/zanyraspi/home-assistant-addons

## Add-ons

This repository contains the following add-ons:

### [Notifiarr](./notifiarr)

This addon is the unified client for Notifiarr.com. The client enables content requests from Media Bot in your Discord Server and also provides reports for Plex usage and system health among many other features.

This add-on will start and create the config file in /config path. The default username is 'admin' and password is available in the log and in the /config/notifiarr.conf

Notifiarr Client documentation: <https://notifiarr.wiki>

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->


