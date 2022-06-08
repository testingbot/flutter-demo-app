# TestingBot Flutter Demo App

This repository contains a Flutter demo app which can be used with [TestingBot's Flutter Automated Testing](https://testingbot.com/support/mobile/flutter.html) example.

## Building

To build the app, simply clone the repository and run
```
flutter build apk --profile
flutter build ios --profile
```

* Note: at the time of writing this, [Appium Flutter Driver](https://github.com/appium-userland/appium-flutter-driver) does not support Flutter >= 3.
We suggest you build this app with Flutter version 2.5.1 - you can use [fvm](https://fvm.app/) to install this version.

## Automated Testing

Once the app is built, upload it to a public URL and follow the [Flutter Automated Testing example](https://testingbot.com/support/mobile/flutter.html) to run your first automated test.
