# Midterm Assignment Using Group Project MemoClub 

This is to show the integration testing and the addition of Ads within the app

To run the integration test, run $ flutter drive --driver integration_test/driver.dart --target integration_test/app_test.dart

To see the AdMob specific files, go to the ad_helper.dart file in the root directory of the midterm. 

Original project repo located here: `https://github.com/Jnpk1/Csc4360-Project-1.git`

link to website: `https://github.com/Jnpk1/Csc4360-Project-1`


## Contributors / Authors (ONLY FOR PROJECT, NOT MIDTERM):

* Nathan Larkin
* Drew Hartman
* James Park

## How to run the App:

1. Have all requirements downloaded
2. copy dependencies in `pubspec.yaml` file.
3. In CLI, type`flutter pub get` to install required plugins that were listed in the new `pubspec.yaml file`
4. To run android, in CLI type `flutter run`
5. To run web version instead. In CLI type `flutter run -d chrome --web-hostname localhost --web-port 8887`

## Build ID: 

`com.dhartman5.midterm`

## Requirements:

* flutter 2.0+ is downloaded and installed
* files that were edited within `android/app/scr/main/res/  (necessary for splash screen)
* update contents in `android/app/src/AndroidManifest.xml`
* have all files in `/lib` downloaded
* Android SDK >= 21
* compatible on Android and Web (Chrome OS)
