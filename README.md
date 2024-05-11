# Ubuntu-hacks

Small but frequently needed peaces of code/knowledge I am lazy to discover again and again.

## Disable and enable touchpad

`synclient TouchpadOff=1` / `...=0` - alternatively could be used gui tool

## Disable and enable power management on wifi

`iwconfig wlp0s20f3 power off` - wlp0s20f3 is device id. Depending on PC setup it cen be wlan0 etc. It used to be managed over *NetworkManager*, not it is *Netplan*. Possible to use [TLP](https://linrunner.de/tlp/index.html)
