---
title: Add Android devtools for Flutter from Windows start
description: Configure your Windows system to develop Flutter mobile apps for Android.
short-title: When you started with Windows
---

To add Android as a Flutter app target for Windows, follow this procedure.

## Install Android Studio

1. Allocate a minimum of 7.5 GB of storage for Android Studio.
   Consider allocating 10 GB of storage for an optimal configuration.
1. Install [Android Studio][] {{site.appmin.android_studio}} to debug and compile
   Java or Kotlin code for Android.
   Flutter requires the full version of Android Studio.

{% include docs/install/compiler/android.md
   target='desktop'
   devos='windows'
   time="first" -%}

{% include docs/install/flutter-doctor.md
   target='Android'
   devos='Windows'
   compiler='Android Studio'
   config='WindowsDesktopAndroid' %}

[Android Studio]: https://developer.android.com/studio/install#win
