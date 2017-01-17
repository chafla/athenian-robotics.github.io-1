# Raspberry Pi Notes

## Enable SSH

In order to enable SSH, create a file named ssh in the boot partition prior to booting.

## Enable a camera

To enable a Pi camera:
```bash
$ sudo raspi-config
```

Select the `Interfacing Options` and then the `Camera` option.

## Enable wifi

```bash
$ sudo nano /etc/wpa_supplicant/wpa_supplicant.conf
```
and add a network entry for each SID with which you might want to connect:
```snakeyaml
network={
    ssid="MyWiFiNetwork"
    psk="the_password"
    key_mgmt=WPA-PSK
}
```
## Installing VNC

Install `tightvncserver` with:
 ```bash
 $ sudo apt-get install tightvncserver
```

Start the server with:
```bash
$ tightvncserver
# or
$ tightvncserver -geometry 1920x1080 -depth 24
```

Connect from your Mac by going to Safari and enter URL: `vnc://pi@raspberrypi.local:5901`

A more detailed description is [here](https://smittytone.wordpress.com/2016/03/02/mac_remote_desktop_pi/).

The Raspian directions are [here](https://www.raspberrypi.org/documentation/remote-access/vnc/).

## File sharing

Details are [here](http://www.instructables.com/id/How-to-share-files-between-Mac-OSX-and-Raspberry-P/?ALLSTEPS).

Enable file sharing with:
```bash
sudo apt-get install netatalk
```

