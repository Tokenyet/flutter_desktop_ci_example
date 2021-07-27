# Flutter Desktop startup project with github ci

> A Startup flutter template for desktop development. Use **github-action** to **build cross-platform automatically**.

Support Platform:
- Windows
- Linux
- MacOS

## How does this work?
This project contains dependencies for all platforms (see [build_dependencies](build_dependencies)) and use [github/workflows](.github/workflows) that heavily modified from official [workflows](https://github.com/google/flutter-desktop-embedding/blob/master/.github/workflows/ci.yml) to complete the job.

## Steps to beginners
1. Config
```
 flutter config --enable-windows-desktop
 flutter config --enable-macos-desktop
 flutter config --enable-linux-desktop
```
2. Run
```
flutter run -d windows # for debug version
flutter run windows # for release version
```
3. Distribution
see [ci.yml](.github/workflows/ci.yml).

## Conculsion
If you like this project, leave a star is the best support! File an issue and PR are also welcome :)
