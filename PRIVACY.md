# Privacy

Move, Brick does not include advertising, analytics, purchases or an account system.

- Your progress (open levels, stars, a level you left unfinished) and your options
  are stored on your device.
- Android backup and device transfer may also copy them, depending on your system
  settings. Move, Brick does not operate a server of its own.
- The updater contacts GitHub for release information and for downloads you request.
  GitHub receives ordinary connection information, including your IP address.
  See [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- Automatic update checks happen at most once a day while the app is open, and at
  once after an update. Downloads and installations require your action; nothing
  runs in the background.
- Downloaded APKs stay in the app's private cache, are excluded from Android
  backup and are temporarily shared with Android's installer. No GitHub token is
  required or stored.
- The app requests two Android permissions: internet access (for the update check)
  and the permission to ask Android to install its own update. A third entry in the
  app's manifest, `de.shakie.movebrick.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`, is
  added by the AndroidX library; it only shields the app's own internal messages
  and gives access to nothing.

Android, your browser and Google Play Protect have their own data handling and
security checks. This document describes Move, Brick, not those external services.
