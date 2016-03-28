# ffmpeg-tutorial
ffmpeg tutorial (ffmpeg 3.0, SDL 2)

This is an ffmpeg 3.0 and SDL 2 adaptation of the ffmpeg tutorial at http://dranger.com/ffmpeg/ffmpeg.html

This work is licensed under the Creative Commons Attribution-Share Alike 2.5 License. 
To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/2.5/ or 
send a letter to Creative Commons, 543 Howard Street, 5th Floor, San Francisco, California, 94105, USA.

Code examples are based off of FFplay, Copyright (c) 2003 Fabrice Bellard, and a tutorial by Martin Bohme. 

## ffmpeg installation on OSX (via Homebrew)

1. Install xcode commandline tools `xcode-select --install` (also installs ruby)
2. Install Homebrew. ` ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
3. Homebrew installation of ffmpeg on OSX For example with all options:

``brew install ffmpeg --with-fdk-aac --with-ffplay --with-freetype --with-frei0r --with-libass --with-libvo-aacenc --with-libvorbis --with-libvpx --with-opencore-amr --with-openjpeg --with-opus --with-rtmpdump --with-schroedinger --with-speex --with-theora --with-tools``

## SDL2 on OSX

1. Download development library from `http://www.libsdl.org/download-2.0.php`
2. Copy `SDL2.framework` to `/Library/Frameworks/`
