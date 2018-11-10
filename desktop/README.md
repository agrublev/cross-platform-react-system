# Desktop

Simple electron app to run a website

## Directory Structure

* `release/` - the release build for each platform (mac, win, linux)
* `resources/` - the resources folder (icons, images ...)
* `src/` the source code of electron application

## Scripts

The project uses [Electron-builder](https://www.electron.build/)  to package & build a ready for distribution Electron app for macOS, Windows and Linux with “auto update” support out of the box.

* `start` - run electron app in development mode.
* `package` - Build unpacked dir. Useful to test.
* `package:<target>` build electron app for target platform (mac, linux, win).
* `package:all` - build electron app for all platform.
