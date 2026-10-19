# Hush releases

Installers for Hush, an end-to-end-encrypted chat, voice and screen-sharing
app. This repository holds only releases; the source isn't here.

Download the newest from the [latest release](../../releases/latest):

- **Windows:** `Hush-<version>-windows-x64.exe` (unsigned: on the SmartScreen
  warning choose *More info → Run anyway*)
- **Linux:** `Hush-<version>-linux-x86_64.AppImage`

Check a download against the release's `SHA256SUMS.txt`.

Hush updates itself from here. Each release carries a `latest.json` signed with
Hush's release key, and the app installs only a release whose signature and
installer hash check out, so a file changed on the way, or here, is refused.
