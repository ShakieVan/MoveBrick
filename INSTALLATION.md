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
Granting the first does not mean Google has approved the app.

## Google Play Protect

**Play Protect blocked version 1.0.0 in a test on November 24, 2026.** On an
Android 16 emulator, during an update through the app, Android first recommended
a scan because Play Protect did not know the app. After the scan, Play Protect
reported "Schädliche App blockiert" (harmful app blocked) with the text "Diese
App könnte schädlich sein" (this app may be harmful). It named no specific
behaviour or file. A second attempt was blocked the same way. The block was not
overridden and Play Protect was not switched off; the installation was not
completed in that test.

[VirusTotal](https://www.virustotal.com/gui/file/553f5e0637dac57546ddb6e13dbb588217b9f36b1bae68d2c36fa5b988044610)
analysed the same file on November 24, 2026: 0 of 64 engines detected anything,
Google's among them; nine further engines could not process the file type, which
is not a clean result. A scanner result does not show how Play Protect on a
device rates the app.

The classification is unexplained. It is neither confirmed as a false alarm nor
withdrawn by Google, and nothing here is a clearance. What the app asks of
Android is listed in [PRIVACY.md](PRIVACY.md): internet access for the update
check and the permission to ask Android to install its own update. Read Play
Protect's message on your device and decide for yourself.

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

Results of real updates through the app are recorded here as they are made.

- **November 24, 2026, to 1.0.0, Android 16 emulator: not completed.** An older
  local test build (0.9.0) found 1.0.0, downloaded it and verified its size,
  checksum, package, version and signing certificate. Android's installer asked
  for confirmation. Google Play Protect then blocked the installation after its
  requested scan (see above); the older build stayed installed.
- **November 24, 2026, to 1.0.0, repeated: installed after the owner's override.**
  Play Protect showed the block again. This time the app's owner chose "Trotzdem
  installieren" (install anyway) under "Weitere Details" on the test emulator.
  Android then installed 1.0.0; the installed file matched the public one byte
  for byte, the progress made before was still there, and on first opening the
  app offered to switch its installation permission off again, which was done.
  This shows that the update works, not that Play Protect accepts the app.
