[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Breezeicons-devices-64-audio-card.svg/64px-Breezeicons-devices-64-audio-card.svg.png)](https://nodesource.com/products/nsolid)

# Yotimix
(just to learn pyqt)
Yotimix is a python software used to select the default audio device and its profile. It should be compatible with bluetooth devices even if other mixers don't work. Actually, in addition to set the audio card as default device, the program desactivate the 
others.

[![N|Solid](http://hpics.li/0936457)](https://nodesource.com/products/nsolid)

# Requirements
| Software | URL |
| ------ | ------ |
| Python3 | https://www.python.org/ |
| amixer| https://www.alsa-project.org/main/index.php/Main_Page (may be installed)|
| PulseAudio (pacmd) | https://www.freedesktop.org/wiki/Software/PulseAudio/ (may be installed)|
| pyQt5 | https://www.riverbankcomputing.com/software/pyqt/ |
| python_subprocess | https://docs.python.org/3.6/library/subprocess.html#module-subprocess |

With shell:
```sh
$ apt-get install python3
$ apt-get install alsa-base
$ apt-get install pulseaudio
$ apt-get install pyqt5-dev
$ apt-get install python3-ptyprocess
