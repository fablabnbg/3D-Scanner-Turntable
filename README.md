# 3D-Scanner-Turntable
Controlling the fancy turntable of the [David SLS 3D Scanner at FablabNürnberg](https://wiki.fablab-nuernberg.de/w/David_SLS2)

<img width=500 src="https://github.com/fablabnbg/3D-Scanner-Turntable/raw/master/photos/20171022_012423.jpg"/>

The turntable hardware was built as a student project. At that time, a simple arduino sketch was done to demonstrate that the table actually works. Each button press advanced the table by 30°. Hardcoded.

<img height=200 src="https://github.com/fablabnbg/3D-Scanner-Turntable/raw/master/photos/20180215_111639.jpg"/>&nbsp;&nbsp;<img height=200 src="https://github.com/fablabnbg/3D-Scanner-Turntable/raw/master/photos/20180112_201006.jpg"/>
<p><br><p>

## Here is an improved version of the turntable controller

* Button press moves triggers a rotation, and then a scan. Send F5 via USB-HID to the David software.

* Different rotation angles (and direction) is configurable.

* Automate a complete 360° scan loop using a windows software that controls the Arduino via USB serial.
