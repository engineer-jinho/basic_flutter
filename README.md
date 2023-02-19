# flutter
flutter 1.9 이후로 사용 안 한지 너무 오래되서 다 까먹음. 다시 앱 개발을 시작하게 되서 기록 시작

자세한 내용은 다음 링크 참조
https://engineer-jinho.github.io/basic_flutter/

# Installation

## Flutter (Version 3.7.3)
https://docs.flutter.dev/get-started/install/macos#get-sdk

- Download then move to "HOME/flutter"
- Check rc with "echo $SHELL"
- nano $HOME/.zshrc
    - export PATH="$PATH:$HOME/flutter/bin"
- 적용: source $HOME/.zshrc
- Check path with "echo $PATH"
- Check flutter "which flutter"
- Check flutter version "flutter --version"

## Android Studio (Version 2022.1.1 Patch 1)
- https://developer.android.com/studio
- Plugin install: Flutter, Dart
- SDK install: Android SDK Tools(Obsolete), Android SDK Command-line Tools(lastest)
- Create Project: Generators --> Fullters --> Android language "Kotlin", iOS "Swift"
- Creat Simulator: Tools --> Device Manager --> Create Device --> Nexus 6, PIE android 9.0, Graphics Hardware (recommended)

## Java
- check Flutter setup with "Flutter doctor -v"
- Requirement Java and get exact version

## Xcode version (14.2)
- Download Xcode: using Mac App Store
- Running Xcode
- sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
- sudo xcodebuild -runFirstLaunch

