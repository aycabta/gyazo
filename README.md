# Gyazo for Linux
This is my own replacement for the official Gyazo for Linux.
It offers many improvements as well as all the features of the official client.

## Installation & Usage
You will need ruby 1.9, scrot and curl.  
Just add the `gyazo` executable to a directory in your PATH (e.g. `~/bin`).  
It doesn't take arguments, so usage is as simple as running `gyazo`.

## Improvements
Despite differences in implementation, all original features are supported.

- Much lighter, shorter, and cleaner than the original
- Uses the lighter scrot over ImageMagick (circumventing ImageMagick issues)
- Executes curl over utilizing net/http
- Does not remove images after uploading them