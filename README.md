# Installing OpenBSD/arm64 on RockPro64


Original Reference: https://github.com/jasperla/openbsd-rockpro64

All I had to do was:

* flash u-boot into the onboard SPI memory (as per jasperla's instructions)
* install the official arm64 miniroot68.img via sdcard and USB-serial adapter



```
# Connect USB-Serial to openbsd machine 
doas cu -l cuaU0 -s 115200

```
