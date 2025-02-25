---
title: Add Android devtools for Flutter from macOS start
description: Configure your Mac to develop Flutter mobile apps for Android.
short-title: When you started with macOS
---

To add Android as a Flutter app target for macOS, follow this procedure.

## Install Android Studio

1. Allocate a minimum of 7.5 GB of storage for Android Studio.
   Consider allocating 10 GB of storage for an optimal configuration.
1. Install [Android Studio][] {{site.appmin.android_studio}} to debug and compile
   Java or Kotlin code for Android.
   Flutter requires the full version of Android Studio.

{% include docs/install/compiler/android.md
   target='macos'
   devos='macOS'
   time="first" -%}

{% include docs/install/flutter-doctor.md
   target='Android'
   devos='macOS'
   config='macOSDesktopAndroid' %}

[Android Studio]: https://developer.android.com/studio/install#mac
