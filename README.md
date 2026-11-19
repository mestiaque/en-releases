# EN apps — releases

Install files and update information for the EN apps by M. Estiaque Ahmed Khan
(ENViewer, ENPlayer, ENBrowser, ENSave, ENRecorder, ENPost, ENStream, ENiShare, ENDisk, ENDB).

- **Downloads:** see [Releases](../../releases) — each release is tagged `<app>-v<version>`.
- **Update information:** `<app>.json` in this repository is the latest release of that app, in the
  shape of a GitHub release (`tag_name`, `body`, `html_url`, `assets[]` with `browser_download_url`,
  `size` and `digest`). The apps read it from `raw.githubusercontent.com` to check for updates, and
  install a file only when its SHA-256 matches `digest`.

This repository holds no source code.

Website: https://mestiaque.com
