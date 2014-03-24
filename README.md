rtl8812AU_8821AU_linux
======================

rtl8812AU_8821AU linux kernel driver for AC1200 (801.11ac) Wireless Dual-Band USB Adapter


From http://askubuntu.com/questions/368015/problem-with-building-compiling-a-driver-for-edimax-wireless-adapter-ew-7822uac

Whenever a new kernel version is installed, reboot then:

```
make clean
make
sudo make install
sudo modprobe 8812au
```
