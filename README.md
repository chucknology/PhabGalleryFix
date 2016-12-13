# PhabGalleryFix
Fixed Gallery3D app for Lenovo Phab 2 devices.

This will allow you to install apps which fail to install with Error -505 because they request gallery permissions, such as Google+.

---
Install with `adb install -r -d PhabGalleryFixed.apk`

Install any apps which previously fail to install, such as G+.

The Gallery app will no longer be functional. Uninstall this update to restore the working functionality of the Gallery app:

Open `Settings`->`Apps`->`Gallery`, select the overflow menu in the top right (three dots) and `Uninstall updates`.

After you uninstall this fix, you may need to repeat the process when affected apps such as G+ are updated.

---
Android source here:
https://android.googlesource.com/platform/packages/apps/Gallery2/

Apache Software License, Version 2.0
