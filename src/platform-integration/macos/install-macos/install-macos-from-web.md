---
title: Add macOS devtools to Flutter from web start
description: Configure your system to develop Flutter mobile apps on macOS.
short-title: When you started with web
---

To add macOS as a Flutter app target for macOS, follow this procedure.

## Install Xcode

1. Allocate a minimum of 26 GB of storage for Xcode.
   Consider allocating 42 GB of storage for an optimal configuration.
1. Install [Xcode][] {{site.appnow.xcode}} to debug and compile native
   Swift or ObjectiveC code.

{% include docs/install/compiler/xcode.md
   target='macOS'
   devos='macOS'
   time="first" -%}

{% include docs/install/flutter-doctor.md
   target='macOS'
   devos='macOS'
   config='macOSDesktopWeb' %}

[Xcode]: {{site.apple-dev}}/xcode/
