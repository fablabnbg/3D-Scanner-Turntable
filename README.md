# 3D-Scanner-Turntable
Controlling the fancy turntable of the [David SLS 3D Scanner at FablabNürnberg](https://wiki.fablab-nuernberg.de/w/David_SLS2)

The turntable hardware was built as a student project. At that time, a simple arduino sketch was done to demonstrate that the table actually works. Each button press advanced the table by 30°. Hardcoded.

## Here is an improved version of the turntable controller

* Button press moves triggers a rotation, and then a scan. Send F5 via USB-HID to the David software.

* Different rotation angles (and direction) is configurable.

* Automate a complete 360° scan loop using a windows software that controls the Arduino via USB serial.
