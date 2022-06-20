usbtop
======

usbtop is a top-like utility that shows an estimated instantaneous bandwidth on
USB buses and devices.


Project status
--------------

Current stable release is 1.0 (tag release-1.0).

The project is stable and has been tested on debian systems. It should work on all different flavors of Linux though.
Do not hesitate to report any issue you would have while trying to compile and run usbtop.

A ncurses and Qt interfaces with a Windows port are the next steps. Feel free to contribute :)


Usage
-----

Please refer to the ```INSTALL.md``` file for installation instructions.
Then, you need to have the ```usbmon``` module loaded. As root, do :

```
# modprobe usbmon
```

Moreover, on some distributions, usbtop need to be run as root!

run (as root or `sudo`)

```
# sudo usbtop
```

USBtop output a table (that is refreshing)
containing USB
bus/device Ids, present band width and total transfered (since it is running).

```
Bus ID 0 (All USB buses)	bw To device	bw From device	tot. To device	tot. From device
  Device ID   1 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   2 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   3 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   4 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
Bus ID 1 (USB bus number 1)	bw To device	bw From device	tot. To device	tot. From device
  Device ID   1 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   2 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   3 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
  Device ID   4 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB
Bus ID 2 (USB bus number 2)	bw To device	bw From device	tot. To device	tot. From device
  Device ID   1 :		0.00 kB/s	0.00 kB/s	0.00 MB		0.00 MB

```
