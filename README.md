# Gyazo for Linux

## Changes
- Threw out the old script and burned it.
- Replaced ImageMagick with scrot
    - Fixes of an issue with windows behind target windows appearing in image
    - No longer requires the heavy ImageMagick
- Replaced net/http with dependency on curl command
- Archives user images in chosen folder