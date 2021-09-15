# Slackware15-Reposity Python
*Python-based programs slackbuilds for Slackware 15.0 Stable ( x86_64 / i586 ).*

SlackBuilds Repository specific for python-based programs.

### Hypnotix Installation

https://github.com/linuxmint/hypnotix

Hypnotix is an IPTV streaming application with support for live TV, movies and series.<br/>
It can support multiple IPTV providers of the following types: M3U URL, Xtream API and Local M3U playlist.<br/>
It has the following dependencies:
```
- dconf              : Already installed.
- hicolor-icon-theme : Already installed.

- python-cairo --> pycairo : Already installed.
- python-requests          : Already installed.
- python-imdbpy            : Not installed. ( python3-imdbpy ).
- python-setproctitle      : Not installed. ( python3-setproctitle ).
- youtube-dl               : Optional.

- libxapp --> xapp : Not installed.
- libmpv  --> mpv  : Not installed.
```
Use instructions for installing *MPV*:
```
- mpv.SlackBuild (in SlackBuilds)
- libass.SlackBuild (in SlackBuilds)
- libplacebo.SlackBuild (in SlackBuilds)
- lua.SlackBuild  (in SlackBuilds)
- mujs.SlackBuild (in SlackBuilds)
```
To work, install the following SlackBuilds:
```
- hypnotix.SlackBuild
- python3-imdbpy.SlackBuild
- python3-setproctitle.SlackBuild
- youtube-dl.SlackBuild

- xapp.SlackBuild (in SlackBuilds)
- libgnomekbd.SlackBuild (in SlackBuilds) (xapp dependency)
```

### Kazam Installation

https://launchpad.net/~sylvain-pineau/+archive/ubuntu/kazam

Kazam is a simple screen recording program that will capture the content of your screen and record a video file that can be played by any video player that supports VP8/WebM video format.<br/>
Optionally you can record sound from any sound input device that is supported and visible by PulseAudio.<br/>
It has the following dependencies:
```
- gstreamer        : Already installed.
- gst-libav        : Already installed.
- gst-plugins-base : Already installed.

- libcanberra : Already installed.
- libwnck3    : Already installed.
- libkeybinder3 >-->> keybinder3 : Already installed.

- python-distutils-extra : Not installed.
- python-cairo   >-->> pycairo     : Already installed.
- python-dbus    >-->> dbus-python : Already installed.
- python-gobject >-->> pygobject3  : Already installed.
- python-xdg     >-->> pyxdg       : Already installed.
```
To work, install the following SlackBuilds:
```
- kazam.SlackBuild
- python-distutils-extra.SlackBuild
```

### ProtonVPN Installation

https://protonvpn.com/

High-speed Swiss VPN that safeguards your privacy.<br/>
To work, install the following SlackBuilds:
```
For cli:
- protonvpn-cli.SlackBuild
- python3-docopt.SlackBuild
- python3-Jinja2.SlackBuild
- python3-MarkupSafe.SlackBuild (python3-Jinja2 dependency)
- python3-pythondialog.SlackBuild

For gui:
- protonvpn-gui.SlackBuild
- python3-ConfigParser.SlackBuild
```

### Transmageddon Installation

http://www.linuxrising.org/


Transmageddon is a video transcoder for Linux and Unix systems built using GStreamer.<br/>
It supports almost any format as its input and can generate a very large host of output files.<br/>
To work, install the following SlackBuilds:

```
- Gtk3    --> gtk+3   : Already installed.
- Glib2   --> glib2   : Already installed.
- Python3 --> python3 : Already installed.
- lsdvd               : Not installed.

- notify-python     --> python-notify2 : Already installed.
- python3-gobject   --> pygobject3     : Already installed.
- xdg-user-dirs-gtk --> xdg-user-dirs  : Already installed.

- GStreamer-1.x              --> gstreamer         : Already installed.
- GStreamer libav 1.x        --> gst-plugins-libav : Already installed.
- GStreamer Plugins Bad 1.x  --> gst-plugins-bad   : Not installed.
- GStreamer Plugins Base 1.x --> gst-plugins-base  : Already installed.
- GStreamer Plugins Good 1.x --> gst-plugins-good  : Already installed.
- GStreamer Plugins Ugly 1.x --> gst-plugins-ugly  : Not installed.
```
To work, install the following SlackBuilds:
```
- transmageddon.SlackBuild

- gst-plugins-ugly.SlackBuild (in SlackBuilds)
- gst-plugins-bad.SlackBuild (in SlackBuilds)
- lsdvd.SlackBuild (in SlackBuilds)
```

### youtube-dl Installation

https://youtube-dl.org/

youtube-dl is a command-line program to download videos from YouTube and a few more sites.<br/>
It requires the Python interpreter, version 2.6, 2.7, or 3.2+, and it is not platform specific.<br/>
It should work in your Unix box, in Windows or in Mac OS X.<br/>
To work, install the following SlackBuilds:
```
- youtube-dl.SlackBuild
```
