# SD Cards Notes

## Burn an SD card

### OSX 

Download a [Raspian](https://www.raspbian.org) image frome [here](https://www.raspberrypi.org/downloads/)

Use [Etcher](https://etcher.io) to burn an image file to an SD card.

## Copy an SD card

### OSX 

Insert an SD card and determine the mount point with:
```bash
$ diskutil list
```

If the mount point were */dev/disk3*, copy the contents to *~/Desktop/raspberrypi.dmg* with:
```bash
$ sudo dd if=/dev/disk3 of=~/Desktop/raspberrypi.dmg
```

After creating the *.img* file, use [Etcher](https://etcher.io) to burn the image file to an SD card.