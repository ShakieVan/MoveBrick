# Move, Brick

**Get out the way!**

A 3D puzzle for Android. A figure built of bricks floats in space, and every brick
carries an arrow. Tap a brick and it flies off along its arrow, but only if no other
brick stands in its way. Clear them all and the level is done.

<p align="center">
  <img src="media/title-1.0.0.png" width="250" alt="Title screen of Move, Brick: the title in heavy slanted letters, the subtitle Get out the way! on an orange band, a figure of clay-coloured bricks with arrows below" />
  <img src="media/level-24-1.0.0.png" width="250" alt="Level 24: a stepped pyramid of 165 clay-coloured bricks, each with an arrow, a dot or a cross" />
  <img src="media/level-33-colour-1.0.0.png" width="250" alt="Level 33 with the colour aid: a flat slab of 200 bricks, coloured by the direction of their arrows" />
  <br />
  <em>Move, Brick 1.0.0 · Screenshots from an Android 16 emulator, November 24, 2026</em>
</p>

**[Download the latest version](https://github.com/ShakieVan/MoveBrick/releases/latest)**
· [Installing and updating](INSTALLATION.md) · [Privacy](PRIVACY.md)

> [!WARNING]
> **Google Play Protect blocked version 1.0.0 in a test on November 24, 2026**
> ("this app may be harmful", without naming a reason). VirusTotal reported 0 of 64
> detections for the same file. The classification is unexplained and not cleared.
> Details: [INSTALLATION.md](INSTALLATION.md#google-play-protect).

## What you get

- **Tap, turn, zoom:** a tap sends a brick off or makes it bump into the one in its
  way. Drag to turn the figure, use two fingers to zoom and to shift it. Since
  1.1.1 the figure stays upright while you turn it: up is always up.
- **Readable from every side:** an arrow shows where a brick goes. A dot means it
  comes towards you, a cross means it goes away from you.
- **Endless levels:** they are computed, start with a handful of bricks and grow to
  about 300, as cubes, walls, stairs, pyramids, crosses, balls, rings and more.
  Every level can be solved.
- **No clock unless you want one:** playing against time is an option and is off
  at first. There is no limit of moves; a nearly clean run earns three stars.
- **Two kinds of level** (since 1.1.0): "Lösbar" (solvable) arranges the arrows so
  that every figure can be cleared. "Zufall" (chance) leaves them to pure chance;
  the figure usually gets stuck, and the app tells you when no brick can leave.
- **Help when you are stuck:** a hint lets a free brick flash. You can also turn all
  arrows around, clear five bricks, or shuffle the arrows: once per level each in
  solvable levels, without limit in levels of chance.
- **Signs as you like them:** the dot and the cross can be switched off (since
  1.1.0), and optionally the colour of a brick shows its direction.
- **Your level waits:** a level you leave is kept and continued later.
- **No advertising, no purchases, no account.** The internet is used only to look
  for updates.

The app's texts are currently in German.

## Requirements

Android 9 or later and OpenGL ES 3.0. The app is distributed as an APK from this
page, outside Google Play, and updates itself from here when you ask it to.

## What was checked

Versions 1.1.0 and 1.1.1 were played on an Android 16 emulator: both kinds of
level, the options, the helps and the upright turning; they were not checked on a
phone.

Version 1.0.0 was played on an Android 16 emulator: the first levels to the end,
a level of about 300 bricks, the hint and the three helps, pause, options and
continuing a level. On a Galaxy S21 (Android 15) the start, the first level and one
move were looked at. Sound, vibration and the two-finger gestures were not checked
before publication. An update to 1.0.0 through the app was downloaded and verified
on the emulator, but Google Play Protect blocked its installation; see
[INSTALLATION.md](INSTALLATION.md#update-results).

## About this repository

This repository distributes the app: release files, checksums and these documents.
It does not contain the source code, and being public does not grant an open-source
license to the app. Licenses of the libraries inside the app are listed in
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Version history

- **1.1.1** (November 24, 2026): turning keeps the figure upright.
- **1.1.0** (November 24, 2026): a second kind of level with arrows by pure chance,
  the dot and the cross can be switched off, figures fill the screen better.
- **1.0.0** (November 24, 2026): first public version.
