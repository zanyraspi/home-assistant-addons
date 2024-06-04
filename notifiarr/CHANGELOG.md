<!-- https://developers.home-assistant.io/docs/add-ons/presentation#keeping-a-changelog -->
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
