# Flutter Desktop startup project with github ci

> A Startup flutter template for desktop development. Use **github-action** to **build cross-platform automatically**.

Support Platform:
- Windows
- Linux
- MacOS

## How does this work?
This project contains dependencies for all platforms (see [build_dependencies](build_dependencies)) and use [github/workflows](.github/workflows) that heavily modified from official [workflows](https://github.com/google/flutter-desktop-embedding/blob/master/.github/workflows/ci.yml) to complete the job.

## Prerequisite
See requirement part from official [https://flutter.dev/desktop#requirements](https://flutter.dev/desktop#requirements).

## Steps to beginners
1. Config
```
 flutter config --enable-windows-desktop # windows devs
 flutter config --enable-macos-desktop # macos devs
 flutter config --enable-linux-desktop # linux devs
```
2. Run hello world
```
flutter run -d windows # for debug version
flutter run -d macos
flutter run -d linux
flutter run windows # for release version 
```
3. Distribution
see [ci.yml](.github/workflows/ci.yml).

**notice: The project you can build is decided by the machine os.**

## Conculsion
If you like this project, leave a star is the best support! File an issue and PR are also welcome :)
