# XQuartz Notes

`XQuartz` is an X server for OSX.

## Installation:
Download and install XQuartz from [here](https://www.xquartz.org).

On OSX, type:
```bash
$ xterm + raspberrypi.local
```

On the Raspberry Pi, add this line to ~/.profile:
```
DISPLAY=pleiku.local:0.0 ; export DISPLAY
```

To verify the setup, type this on the Raspberry Pi:
```bash
$ lxsession
```

