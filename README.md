# Gyazo for Linux

## Changes
- Threw out the old script and burned it.
- Replaced ImageMagick with scrot
    - Fixes of an issue with windows behind target windows appearing in image
    - No longer requires the heavy ImageMagick
- Replaced net/http with curl because net/http is ugly.
- Archives user images in chosen folder
- Does not support proxies. This will be remedied if I ever get to it.