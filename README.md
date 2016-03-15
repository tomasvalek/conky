# Conky
Based on https://github.com/brndnmtthws/conky software.

### Installation of Conky, lm-sensors
```sh
$ sudo apt-get install conky lm-sensors
$ sudo sensors-detect
$ sudo module-init-tools start
Copy file: .conkyrc to ~/ directory
```
### Set Conky to start after 5s at boot (for Gnome)
```sh
Press Alt+F2
Type gnome-session-properties
Press enter
Click add

Name: Conky
Command: conky -p 5
```

###Screenshot (click for fullscreen)
![Screenshot](screenshot.jpeg?raw=true)
