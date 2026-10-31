# Naxora AR — releases

Public distribution repository for the Naxora AR Android app. The app itself checks the latest release here and offers updates.

## Install
1. Download `Naxora-<version>.apk` from the latest release on the **Releases** page (right-hand side).
2. Open it on your phone. If Android asks, allow your browser / file manager to "Install unknown apps".
3. Later versions are offered inside the app (home screen → **Check for updates**). Android always asks you to confirm an install.

Requires Android 10 or newer (API 29) and a device that supports ARCore.

## For maintainers
* Every release has a tag `vX.Y.Z` and two files: `Naxora-X.Y.Z.apk` and `naxora-update.json` (see `update/naxora-update.json.example`).
* The `latest` release must **not** be a pre-release: the app reads `releases/latest/download/naxora-update.json`.
* Never upload keystores or passwords. See the Unity project's `docs/UPDATES.md` for the full procedure.
