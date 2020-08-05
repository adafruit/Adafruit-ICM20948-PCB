## Adafruit ICM20948 9-DoF IMU PCB

<a href="http://www.adafruit.com/products/4554"><img src="assets/4554.png?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ICM20948 9-DoF IMU. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4554

### Description
When you want to sense orientation using inertial measurements, you need an Inertial Measurement Unit, and when it comes to IMUs, the more DoFs, the better! The ICM20948 from Invensense packs 9 Degrees of freedom into a teeny package, making it a one stop shop for all the DOFs you need! Within it’s svelte 3x3mm package there are not just one MEMS sensor die like your common sensors, but two sensor dies! The ICM20948 pair’s Invensense’s MEMS 3-axis accelerometer and gyro with the AK09916 3-axis magnetometer from Asahi Kasei Microdevices Corporation.

 All 9 axes of measurement are made available thanks to a crew of 16-bit Analog to Digital Converters, diligently converting the raw analog signals from the MEMs sensors to digital readings that are accessed via I2C or SPI. Each of the sensors have the quality specs you would expect from such a sensor. Just see what the datasheet has to say:

• 3-Axis Gyroscope with Programmable FSR of ±250 dps, ±500 dps, ±1000 dps, and ±2000 dps

• 3-Axis Accelerometer with Programmable FSR of ±2g, ±4g, ±8g, and ±16g

• 3-Axis Compass with a wide range to ±4900 µT

Now that’s a handy and capable team of sensors, ready to help orient your project in the right direction!


Like any high performance device the ICM20948 can a bit particular about how it needs to be worked with. Unlike the pick and place machines that normally handle these sensors, most of us humans can’t readily take a little guy like the ICM20948 and plop it into our circuit; it’s small! What’s more, the ICM20948 runs on 1.8V which is increasingly common for device manufacturers but isn’t hardly common for makers, learners, prototypers or the like. With that in mind, we’ve put the ICM20948 on a breakout with a 1.8V voltage regulator as well as level shifting circuitry to allow your 3.3V device such as a Feather M4 or Raspberry Pi, or a 5V device such as the Arduino Uno.

To make connections easy, our breakout puts makes the pins of the ICM20948 available on standard 0.100”/ 2.54mm pitch headers for use with a breadboard. Should you wish to avoid soldering, the Stemma QT form factor breakout also includes our Stemma QT connectors which just like the SparkFun Qwiic connectors they’re inspired by (and compatible with). Using these handy connectors you can simply plug in the sensor and get rolling with your project. You can even use them to daisy chain multiple sensors together! All of this is explained with wiring diagrams for use with Arduino or CircuitPython on the pages to come.


Lastly, all the wiring in the world wouldn’t do you much good if you didn’t know how to use those wires to talk to your sensor, so we’ve done the work of writing libraries for Arduino and CircuitPython that will allow you to use the ICM20948 with your favorite development board, be it an Arduino, Feather, Raspberry Pi, or one of the many other Arduino and CircuitPython compatible boards.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
