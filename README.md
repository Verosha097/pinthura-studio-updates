# Pinthura Studio — updates

This repository only holds the released installers of Pinthura Studio (see **Releases**).
Installed copies of the app check here for new versions and update themselves.

To publish a new version: change `"version"` in the app's `package.json`, then run
`publish-release.bat` in the project folder. It builds the installer and adds a release here
with `Pinthura-Studio-Setup-x.y.z.exe`, its `.blockmap` and `latest.yml`.
