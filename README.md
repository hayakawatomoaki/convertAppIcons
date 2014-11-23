convertAppIcons
===============

convert iOS-App Icons and Android-App Icons from 1024x1024 png.

input:<br>
　1024x1024 png file.<br>

output:<br>
　iOS-App Icons.<br>
　Android-App Icons.<br>

requirements:<br>
　ruby.<br>
　ImageMagic.<br>

## Usage

```
Usage: convertAppIcons [options]
    -i input png-file. [1024x1024]
    -o output directory.

command example:
$ ./convertAppIcons -i sample_icon.png -o out

converted images:
##iOS
Icon-29.png          : 29x29
Icon-29@2x.png       : 58x58
Icon-29@3x.png       : 87x87
Icon-40.png          : 40x40
Icon-40@2x.png       : 80x80
Icon-40@3x.png       : 120x120
Icon-50.png          : 50x50
Icon-50@2x.png       : 100x100
Icon-50@3x.png       : 150x150
Icon-57.png          : 57x57
Icon-57@2x.png       : 114x114
Icon-57@3x.png       : 171x171
Icon-60.png          : 60x60
Icon-60@2x.png       : 120x120
Icon-60@3x.png       : 180x180
Icon-72.png          : 72x72
Icon-72@2x.png       : 144x144
Icon-72@3x.png       : 216x216
Icon-76.png          : 76x76
Icon-76@2x.png       : 152x152
Icon-76@3x.png       : 228
Icon-Small-50.png    : 50x50
Icon-Small-50@2x.png : 100x100
Icon-Small-50@3x.png : 150x150
Icon-Small.png"      : 29x29
Icon-Small@2x.png    : 58x58
Icon-Small@3x.png    : 87x87
Icon.png             : 57x57
Icon@2x.png          : 114x114
Icon@3x.png          : 171x171
Icon-120.png         : 120x120
iTunesArtwork.png    : 512x512
iTunesArtwork@2x.png : 1024x1024
iTunesArtwork@3x.png : 1536x1536

##Android
drawable-hdpi/ic_launcher.png    : 72x72
drawable-ldpi/ic_launcher.png    : 36x36
drawable-mdpi/ic_launcher.png    : 48x48
drawable-xhdpi/ic_launcher.png   : 96x96
drawable-xxhdpi/ic_launcher.png  : 144x144
drawable-xxxhdpi/ic_launcher.png : 192x192
playstore-icon.png               : 512x512
````

## Expects
- Platform has ImageMagic `convert` command.
- Input file must be 1024x1024 PNG format.

## License
MIT Lincense.
