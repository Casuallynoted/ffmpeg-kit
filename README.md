# Fix for `v1 embedding build failure` for flutter

_This is a fork of this original repo: https://github.com/arthenica/ffmpeg-kit_

```bash
dependencies:

  # Original ffmpeg kit for reference. (We will use the custom fork with fix for v1 embedding build failure)
  # ffmpeg_kit_flutter_full_gpl: 6.0.3 # Or check pub.dev for latest

  # --- Use custom fork of ffmpeg-kit with fix for v1 embedding build failure ---
  ffmpeg_kit_flutter: # <--- Use the NAME from the fork's pubspec
    git:
      url: https://github.com/anonfaded/ffmpeg-kit.git # Custom fork URL
      ref: main  # Use the branch you want (e.g., main, or a specific fix branch if you create one)
      path: flutter/flutter # The path to the pubspec with name: ffmpeg_kit_flutter
  # ------------------------------------
```
