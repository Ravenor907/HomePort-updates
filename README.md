# Homeport updates

This repository only hosts finished Homeport app files, so installed apps can
update themselves. There is no source code here.

- **PC (Flatpak):** updates come from the signed Flatpak repository on this
  repository's site, <https://ravenor907.github.io/HomePort-updates/>.
- **Phone app and TV wake helper:** they read `latest.json` from the newest
  release and install the new version (Android checks it is signed with the
  same key as the installed app).

New versions are published here by `tools/publish-updates.sh` in Homeport.
