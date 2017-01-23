# GoPiGo Notes

A GoPiGo can be purchased 
[here](https://www.dexterindustries.com/gopigo/).

A GoPiGo intro is 
[here](https://www.dexterindustries.com/GoPiGo/programming/python-programming-for-the-raspberry-pi-gopigo/).

A GoPiGo overview is 
[here](https://pythonprogramming.net/robotics-raspberry-pi-tutorial-gopigo-introduction/).

## Setup

After plugging in the ethernet cable, connect to the GoPiGo with:
```bash
$ ssh pi@dex.local
Are you sure you want to continue connecting (yes/no)? yes
Password: robots1234
pi@dex:~ $
```

Setup the wifi connection as described under **Enable WiFi** 
[here](http://www.athenian-robotics.org/raspberrypi/#raspberry-pi-notes).

Reboot the GoPiGo with:
```bash
pi@dex:~ $ sudo reboot now
```

After disconnecting the ethernet cable, verify the GoPiGo's Wifi is working with:
```bash
$ ssh pi@dex.local
Password: robots1234
pi@dex:~ $
```
