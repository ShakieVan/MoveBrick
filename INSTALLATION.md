# Installing and Updating Move, Brick

Move, Brick is distributed as an APK through this repository, outside Google Play.
Download only from [Move, Brick Releases](https://github.com/ShakieVan/MoveBrick/releases).
The universal APK works on all supported phones.

## First Installation

1. Download `MoveBrick-X.Y.Z-universal.apk` and open it from your browser or Downloads.
2. If Android requests permission for that source, open its **Settings** link.
   Enable **Allow from this source** only for the app that is opening the APK.
3. Return to the installer and read any security messages before continuing.
4. After installation, you can turn the source's installation permission off again.

Permission to install APKs and a Google Play Protect scan are separate checks.
Granting the first does not mean Google has approved the app. Play Protect may scan
the app or warn about it because it comes from outside Google Play; read its message
before you decide. No claim is made here about how Play Protect rates this app.

## Updates Inside the App

1. Open **Updates** on the title screen. When a newer version is known, the title
   screen also shows a note "Neue Version … verfügbar".
2. Check the available version and its notes, then choose **Update herunterladen**
   (download update).
3. Choose **Update installieren** (install update). If needed,
   **Installationsfreigabe** (installation permission) opens Android's settings
   specifically for Move, Brick.
4. Return to the app and start the installation. Android asks for confirmation.
5. On first opening after an update, the app offers a settings link if its
   installation permission is still active, so you can switch it off again.

For the first download, the permission belongs to your browser or file manager;
for an in-app update it belongs to Move, Brick.

The app looks for updates at most once a day while it is open, and at once after
an update. It downloads and installs nothing on its own. Before installing it
checks the file's size and SHA-256 checksum against GitHub's release data, and the
package name, version and signing certificate against the installed app.

## Checking a Download Yourself

Every release lists the SHA-256 checksum of its APK in `SHA256SUMS.txt`. The app is
signed with one certificate, SHA-256
`45803342c9a463aa7e0d4e999525d6f0f5a89b53c32ed49865e0bdf324476bc0`.
Android refuses an update that is signed with another one.

## Update Results

None yet: 1.0.0 is the first public version. Results of real updates through the
app are recorded here as they are made.
