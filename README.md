# PhabGalleryFix
Fixed Gallery3D app for Lenovo Phab 2 devices.

---
Install with `adb install -r -d PhabGalleryFixed.apk`

Install any social media apps which were previously failing to install with error -505, such as G+.

The Gallery app will no longer be functional. To restore the working functionality of the Gallery app:

Open `Settings`->`Apps`->`Gallery`, select the overflow menu in the top right (three dots) and `Uninstall updates`.

After you uninstall this fix, you may need to repeat the process when affected apps such as G+ are updated.

---
Android source here:
https://android.googlesource.com/platform/packages/apps/Gallery2/

Apache Software License, Version 2.0
