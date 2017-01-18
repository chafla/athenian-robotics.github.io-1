# XQuartz Notes

`XQuartz` is an X server for OSX.

## Installation
Download and install XQuartz from [here](https://www.xquartz.org).

Type this on the Mac:
```bash
$ xterm + raspberrypi
```
Add this line to ~/.profile on the Raspi:
```
DISPLAY=pleiku.local:0.0 ; export DISPLAY
```

Verify the setup on the Raspi with:
```bash
$ lxsession
```

