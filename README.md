# KOVHAX

A Windows aim-assistance client for research and development around target geometry, response curves and mouse input in KovaaK's.

> **Keep assisted runs off leaderboards.** Use this build for private, unranked experiments. Close it before a scored run. An assisted result is not a measure of your own aim.

## Download

[**Download KOVHAX.exe**](https://github.com/InfernoTV/KOVHAX/releases/latest/download/KOVHAX.exe) · [Releases](https://github.com/InfernoTV/KOVHAX/releases)

Windows x64. One EXE; no installer or additional DLLs. This repository distributes the protected binary and its documentation. Source code is not published here.

## Getting started

1. Put the EXE in a writable folder and launch it.
2. Read the startup notice, then choose **Continue**. Aim and trigger assistance start disabled on a fresh installation.
3. Use the browser menu that opens automatically, or press **Insert** while KovaaK's is in focus to open the in-game menu.
4. Select your input backend and calibrate in a private session before enabling assistance.

**Insert** toggles the menu. **F8** requests calibration. **End** closes the client. You can also exit from the browser menu.

Settings, profiles and logs are stored in `KOVHAX-data` beside the EXE. Move that folder with the application to keep them. Existing profiles retain their saved settings when loaded.

The browser menu runs on `127.0.0.1`. Its live session link grants access to the controls; keep that link private.

## What you can explore

- **Target geometry:** closest-point selection on collision capsules, including long targets, plus a configurable body region.
- **Motion response:** six response models, editable Bezier curves, speed and acceleration limits, prediction and a feathered inner deadzone.
- **Visual feedback:** capsule outlines and fills, field-of-view guides and independent color controls.
- **Input:** Windows mouse input or MAKCU, with device discovery, connection status, reconnect and calibration controls.
- **Configuration:** named portable profiles and synchronized settings across the native and browser menus.

The overlay uses recovered collision geometry. It does not render the game's model meshes or material chams. Compatibility depends on the game build and scenario; updates can break it.

## Why is the EXE protected?

The downloadable build is processed with VMProtect to make parts of its implementation harder to reverse engineer. Protection adds startup overhead; it does not make the program impossible to inspect or guarantee that it is safe.

**There is no automatic leaderboard enforcement.** KOVHAX does not detect score submissions, report players to developers or moderators, or issue bans. Obfuscation does not change that. The startup notice is a reminder, not a technical restriction.

Do not submit assisted scores or present them as clean performance.

## Project status

This is an experimental, unofficial project. The release is checked for startup, local controls, configuration and profile persistence. Those checks do not establish compatibility with every scenario or validate live input behavior on every setup.

KOVHAX is not affiliated with or endorsed by KovaaK's or its developers. Third-party component notices are embedded in the EXE and available through **Settings → Third-party notices** in the browser menu.
