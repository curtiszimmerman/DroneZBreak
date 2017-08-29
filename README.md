# DroneZBreak 
by mavicBreak
Change flight controller parameters of DJI Drones and upgrade/downgrade firmware natively on OSX

<img src='https://i.imgur.com/aA7vjUC.png' />

<img src='https://i.imgur.com/23Kl0lj.png' />


**Supported macOS:** Sierra (OSX 10.12), El Capitan (OSX 10.11), might work on Yosemite (OSX 10.10)

`It is an unsigned macOS application which is not allowed to run on OSX by default. If you have problem with starting the application go to System Preferences > Security & Privacy > and enable the execution of the app.`

**Supported drones:** Mavic, Spark, P4P, Inspire 2, might work with other DJI drones

**Supported devices:** Mavic Remote Controller, DJI Goggles


**Features:**
+ Set parameters without DJI Assistant
+ Predefinied Normal+ and Sport+ modes
+ Parameters Factory Reset option
+ Firmware Flashing Utility with progress bar actively monitoring the process
+ One click download & decrypt upgrade log file

**Notes**

DroneZBreak is fail-safe. In case of application crash during firmware or parameter flashing your device is safe. The operation continues on the device itself regardless of the USB cable connection or application state.

If your drone firmware can not be detected upon startup and DroneZBreak gives an error one case might be because your firewall (like LittleSnitch) is blocking DJI Assistant outgoing connections therefore it is blocking the communication with your drone upgrade service. Thx for marck1991 doing a lot of tests to figure this out.

**Links:**

http://dji.retroroms.info/ - "Wiki"

https://github.com/jezzab/DUMLdore - Even windows users need some love, so DUMLDore was created to help archive, and flash dji_system.bin files on windows platforms.

https://github.com/hdnes/pyduml - Original script of firmware multi-platform flashing in Python

https://github.com/MAVProxyUser/DUMLrub - Ruby port of PyDUML, and firmware cherry picking tool. Allows rolling of custom firmware images.

https://github.com/MAVProxyUser/dji_system.bin - Current Archive of dji_system.bin files that compose firmware updates referenced by MD5 sum. These can be used to upgrade and downgrade, and root your I2, P4, Mavic, Spark, Goggles, and Mavic RC to your hearts content. (Use with pyduml, DUMLDore or DroneZBreak)

https://nolimitdronez.com - Alternative solution for Windows users with excellent live support.



Thanks to hostile, the_lord, P0V, hdnes, jezzab, coldflake, freaky123, bin4ry and all the Slack members who spent countless effort and time to figure out all the stuff.
