# Slackware15-Reposity Python
*Programs slackbuilds for Slackware 15.0 Stable ( x86_64 / i586 ).*

SlackBuilds Repository for program sources.

## AcetoneISO Installation

https://launchpad.net/ubuntu/+source/acetoneiso

AcetoneISO makes it possible to easily use various kinds of CD and DVD images on your computer as if they were burned to real CDs.<br/>
You can use the application to mount and manage CD and DVD images.<br/>
Supported disc-image formats are ISO, BIN, NRG, MDF and IMG.<br/>
Use instructions for installing *P7Zip*:
```
- p7zip.SlackBuild
- wxGTK3.SlackBuild
```
To work, install the following SlackBuilds:
```
- acetoneiso.SlackBuild
- cdrkit.SlackBuild
- fuseiso.SlackBuild
- rar.SlackBuild
```

## CPU-X Installation

https://x0rg.github.io/CPU-X/

CPU-X is a Free software that gathers information on CPU, motherboard and more.<br/>
It can be used in graphical mode by using GTK or in text-based mode by using NCurses.<br/>
To work, install the following SlackBuilds:
```
- CPU-X.SlackBuild
- libcpuid.SlackBuild
```

## CodeBlocks Installation

https://www.codeblocks.org/

Code::Blocks is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users.<br/>
It is designed to be very extensible and fully configurable.<br/>
To work, install the following SlackBuilds:
```
- codeblocks.SlackBuild
- wxGTK3.SlackBuild
```

## Conky Complete Installation

https://github.com/zcot/conky-manager2<br/>
https://github.com/MX-Linux/mx-conky<br/>
https://github.com/MX-Linux/mx-conky-data

Conky is a free, light-weight system monitor for X, that displays any kind of information on your desktop.<br/>
To work, install the following SlackBuilds:
```
For Conky:
- conky.SlackBuild
- imlib2.SlackBuild
- tolua++.SlackBuild

For interfaces:
- conky-manager.SlackBuild
- mx-conky.SlackBuild
```

## Eclipse JEE Installation

https://www.eclipse.org/

Tools for developers working with Java and Web applications.<br/>
Including a Java IDE, tools for JavaScript, TypeScript, JavaServer Pages and Faces, Yaml, Markdown, Web Services, JPA and Data Tools, Maven and Gradle, Git, and more.<br/>
To work, install the following SlackBuilds:
```
- eclipse-jee.SlackBuild
```

## FlareGet Installation

https://flareget.com/

FlareGet is a full featured, multi-threaded download manager and accelerator for Windows, Mac and Linux.<br/>
To work, install the following SlackBuilds:
```
- flareget.SlackBuild
```

## Google Chrome Installation

https://www.google.com/chrome/

Powered by Google. Browse with the power of Google.<br/>
To work, install the following SlackBuilds:
```
- google-chrome.SlackBuild
```

## Google Earth Pro Installation

https://www.google.com.br/earth/

The most detailed terrestrial globe in the world.<br/>
To work, install the following SlackBuilds:
```
- google-earth.SlackBuild
```

## MPV Installation

https://mpv.io/

MPV is a free (as in freedom) media player for the command line.<br/>
It supports a wide variety of media file formats, audio and video codecs, and subtitle types.<br/>
It has the following dependencies:
```
- libasound  : Already avaliable in ALSA.
- pulseaudio : Already installed.
- ffmpeg     : Already installed.

- libass     : Not installed.
- libplacebo : Not installed.
- lua        : Not installed.
- mujs       : Not installed.

- jack               : Optional.
- libjpeg            : Optional.
- nvdec              : Optional.
- rubberband         : Optional.
- uchardet           : Optional.
- vaapi              : Optional.
- vapoursynth        : Optional.
- vapoursynth-script : Optional.
- zlib               : Optional.
```
To work, install the following SlackBuilds:
```
- mpv.SlackBuild
- libass.SlackBuild
- libplacebo.SlackBuild
- lua.SlackBuild
- mujs.SlackBuild
```

## Nulloy Installation

https://nulloy.com/

Nulloy is a small, easy-to-use application specially designed to help you listen to your favorite music.<br/>
It has the following dependencies:
```
qt5    : Already installed.
zip    : Already avaliable in zlib.
taglib : Already installed.
libX11 : Already installed.

gstreamer        : Already installed.
gst-plugins-base : Already installed.
gst-plugins-good : Already installed.
gst-plugins-bad  : Not installed.
gst-plugins-ugly : Not installed.
```
To work, install the following SlackBuilds:
```
- nulloy.SlackBuild

- gst-plugins-ugly.SlackBuild (optional)
- gst-plugins-bad.SlackBuild (optional)
```

## Ocenaudio Installation

https://www.ocenaudio.com/

An easy, fast and functional audio editor.<br/>
To work, install the following SlackBuilds:
```
- ocenaudio.SlackBuild
- jack.SlackBuild
```

## P7Zip Installation

https://github.com/jinfeihan57/p7zip

p7zip is a quick port of 7z.exe and 7za.exe (command line version of 7zip, see www.7-zip.org) for Unix.<br/>
7-Zip is a file archiver with highest compression ratio.<br/>
To work, install the following SlackBuilds:
```
- p7zip.SlackBuild
- wxGTK3.SlackBuild
```

## PhotoQT Installation

https://photoqt.org/

PhotoQt is a simple yet powerful and good looking image viewer, based on Qt/QML, published as open-source, and completely free.<br/>
To work, install the following SlackBuilds:
```
- photoqt.SlackBuild
- graphicsmagick.SlackBuild
- libqpsd.SlackBuild
- pugixml.SlackBuild
```

## QBitTorrent Installation

https://www.qbittorrent.org/

The qBittorrent project aims to provide an open-source software alternative to µTorrent.<br/>
Additionally, qBittorrent runs and provides the same features on all major platforms (FreeBSD, Linux, macOS, OS/2, Windows).<br/>
qBittorrent is based on the Qt toolkit and libtorrent-rasterbar library.<br/>
To work, install the following SlackBuilds:
```
- qbittorrent.SlackBuild
- libtorrent-rasterbar.SlackBuild
```

## QMPlay2 Installation

https://github.com/zaps166/QMPlay2

QMPlay2 is a video and audio player.<br/>
It can play all formats supported by FFmpeg, libmodplug (including J2B and SFX).<br/>
It also supports Audio CD, raw files, Rayman 2 music and chiptunes.<br/>
It contains YouTube and MyFreeMP3 browser.<br/>
It has the following dependencies:
```
- alsa-lib     : Already installed.
- ffmpeg       : Already installed.
- libass       : Not installed.
- libcddb      : Already installed.
- libcdio      : Already installed.
- libgl        : Already avaliable in Mesa.
- libgme       : Not installed.
- libpulse     : Already avaliable in PulseAudio.
- libsidplayfp : Not installed.
- libva        : Already installed.
- libxv        : Already installed.
- qt5          : Already installed.
- taglib       : Already installed.
- pulseaudio   : Already installed.
- portaudio    : Not installed.
```
To work, install the following SlackBuilds:
```
- libass.SlackBuild
- libgme.SlackBuild
- libsidplayfp.SlackBuild
- portaudio.SlackBuild
- xa.SlackBuild (libsidplayfp dependency)
```

## SoftMaker Free Office 2018 Installation

https://www.freeoffice.com/

The best free alternative to Microsoft Office.<br/>
For Windows, Mac and Linux.<br/>
To work, install the following SlackBuilds:
```
- freeoffice2018.SlackBuild
```

## Spotify Installation

https://www.spotify.com/

Spotify is a digital music service that gives you access to millions of songs.<br/>
To work, install the following SlackBuilds:
```
- spotify.SlackBuild
```

## Telegram Installation

https://desktop.telegram.org/

Telegram is a cloud-based mobile and desktop messaging app with a focus on security and speed.<br/>
To work, install the following SlackBuilds:
```
- telegram.SlackBuild
```

## UGet Installation

https://ugetdm.com/

uGet, the Best Download Manager for Linux.<br/>
uGet is a lightweight yet powerful Open Source download manager for GNU/Linux developed with GTK+.<br/>
To work, install the following SlackBuilds:
```
- aria2.SlackBuild
- uget.SlackBuild
```

## UMPlayer Installation

https://www.smplayer.info/umplayer

The Universal Media Player, is an application based on SMPlayer 0.6.9, with some extra features like Youtube playback.<br/>
To work, install the following SlackBuilds:
```
- umplayer.SlackBuild
```