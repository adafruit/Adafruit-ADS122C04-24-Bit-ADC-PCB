## Adafruit ADS122C04 24-Bit ADC - 4 Channel 2-kSPS - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6432"><img src="assets/6432.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ADS122C04 24-Bit ADC - 4 Channel 2-kSPS - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6432

### Description

The <b>Adafruit ADS122C04 24-Bit ADC with 4 Channel 2-kSPS</b> is an excellent way to take very high-precision measurements of single-ended or differential analog signals over I2C. Most 24-bit ADCs are found on strain-gauge sensors like the [NAU7802](https://www.adafruit.com/product/4538) and don't have high speeds or configurations. And most fast-ish I2C ADCs like the [ADS1115](https://www.adafruit.com/product/1085) top out at 16 bits. The ADS122C04 is a bit more expensive than either but it's one of the few ADCs we've seen that gives you up to 2000 samples-per-second (on one channel) at 24-bit resolution.

As you can expect from TI, it's a great quality ADC with lots of extras like a reset pin, internal temperature sensor, either single-ended or differential on any of the four inputs, internal 2.048V reference voltage, external positive and negative reference voltage input pins, 3V or 5V power and logic levels, and up to 128x gain. It even has two I2C address pins so you can put four of these on the same I2C bus.

This board would make an excellent data acquisition interface for lots of different scientific or engineering measurements. The I2C interface means its easy to get it working with any microcontroller or microcomputer, from the 8-bit Arduino-compatible to the highest end Raspberry Pi. Note that to get 2kSPS you'll need to run the I2C bus at 1 MHz and process that data from I2C quickly!

Comes with a bit of 0.1" standard header in case you want to use it with a breadboard or perfboard.  Four mounting holes for easy attachment. 

To get you going fast, we spun up a custom-made PCB in the [STEMMA QT form factor](https://www.adafruit.com/?q=stemma%20qt%20sensor), making it easy to interface with. The [STEMMA QT connectors](https://learn.adafruit.com/introducing-adafruit-stemma-qt/what-is-stemma-qt) on either side are compatible with the [SparkFun Qwiic](https://www.sparkfun.com/qwiic) I2C connectors. This allows you to make solderless connections between your development board and the ADS122C04 or to chain it with a wide range of other sensors and accessories using a [compatible cable](https://www.adafruit.com/?q=stemma%20qt%20cable). [QT Cable is not included, but we have a variety in the shop](https://www.adafruit.com/?q=stemma+qt+cable&sort=BestMatch).

We have [example code for both the Raspberry Pi, Arduino, and CircuitPython](https://github.com/adafruit/?q=ads122C04&type=all&language=&sort=). Simply connect GND to ground, VDD to your 3V~5V logic power supply, and SCL/SDA to your microcontroller's I2C port and run the example code to start reading data.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
