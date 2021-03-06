Sound++ player
=====================

Sound++ player is a [GPLv3](LICENSE) licensed MP3/OGG/FLAC/PCM player for Android with the following features:
* multiple playlist support
* grouping by artist, album or genre
* plain filesystem browsing
* [ReplayGain](https://en.wikipedia.org/wiki/ReplayGain) support
* headset/Bluetooth controls
* accelerometer/shake control
* cover art support
* [ScrobbleDroid](https://code.google.com/p/scrobbledroid/) support for Last.fm integration

Contributing
===========
Project tracking
---------------
* Asana link: https://app.asana.com/0/185510055530268/185510055530269

Contributing code
---------------
* Code trên branch riêng
* Backup local trước khi merge

Building
========
To build you will need:

 * A Java compiler compatible with Java 1.7
 * The Android SDK with platform 24 (Nougat) installed

Building from command-line #1
--------------------------
 * `gradle build` to build the APK
 * Optional: `gradle installDebug` to install the APK to a connected device
 
Building from command-line #2
--------------------------
 * `android update project --path .` to generate local.properties
 * `ant debug` to build the APK at bin/VanillaMusic-debug.apk
 * Optional: `ant installd` to install the APK to a connected device

Building with Android Studio
---------------------
You can also build with Android Studio by importing this project into it.

Building from Eclipse
---------------------
You can also build from Eclipse. Create a new Android Project, choosing "Create
project from exisiting source", then set the compiler compliance level to 1.6
in project settings.

Documentation
=============
Javadocs can be generated using `gradle javadoc` or `ant doc`

