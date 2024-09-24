<!-- https://developers.home-assistant.io/docs/add-ons/presentation#keeping-a-changelog -->
## v0.8.2 Sep 23, 2024

https://github.com/Notifiarr/notifiarr/releases/tag/v0.8.2

- Variable values may now be read from additional config files using filepath:
- Adds HA stats to Synology snapshots.
- HTTP assets are stored compressed.
- HTTP responses are now served compressed.
= Builds an Arch Linux package now.

## v0.8.1 Jul 28, 2024

https://github.com/Notifiarr/notifiarr/releases/tag/v0.8.1

- Moves Windows auto updater to a trigger. It now works correctly in all scenarios.
- Cleans up backup executables on Windows.
- Makes X11 GUI support work correctly in Linux.
- Adds an integrity check so we can identify custom clients.
- Service check is now disabled when no services to check exist.
- New trigger interval to send an up-check to the website.
- Removes home-brew builds.
- Nvidia-SMI path can now be removed in UI. App will correctly use PATH to find it.
- Client was, and no longer, sends mysql auth info to the website.
- Fixes a bug in Arch aur package maker than was putting files in /share instead of /usr/share.
- Adds auto-start checkbox to GUI menu.


## v0.7.3 May 29, 2024

https://github.com/Notifiarr/notifiarr/releases/tag/v0.7.3

- Fixes Docker Cloud build.
- Prevents latest tag on GHCR from being random.
- Fixes macOS app (crashes on startup).
- Sets a log file path if a directory was provided (instead of throw errors).
- Adds an unstable update feature for dev/test users using Mac and windows.

## v0.7.1 May 26, 2024

https://github.com/Notifiarr/notifiarr/releases/tag/v0.7.1

- Docker images are now built in GitHub actions and served from GitHub Container Registry.
- _Note: Images (without a rate limit) are still built by and available on Docker Hub._

## v0.7.0 (Initial HAOS Addon Release)

- Make Plex scrobble web hook more useful.
- Accelerate Radarr movie API requests.
- Enable log file upload button in the UI.
- Allow deleting media, with rate limit.
- Add standard download client integration for Transmission.
- New logo.
- Squash bugs you didn't even know were there.
