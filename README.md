## Adafruit VCNL4030 Proximity and Lux Sensor - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6491"><img src="assets/6491.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VCNL4030 Proximity and Lux Sensor - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6491

### Description

The VCNL4030 is a handy two-in-one sensor, with a proximity sensor that works from <b>0 to 300mm</b> (about 12 inches) and light sensor with range of <b>0.004 to 16,768 lux</b>.

We've all been there. That thing is close but how close? When you need to measure a small distance with reasonable accuracy, such as the rough height of particularly calm bumble bee, the VCNL4030 Proximity Sensor from Vishay can do that for you. If perchance you also needed to measure the amount of light at the same time, perhaps to let the bee to know if it's time for bed, you're in luck! The VCNL4030 can do that too (bumble bee not included, we tried putting it in the anti-static bag but it started buzzing in a threatening manner)

<b>Note there's quite a few chips in the VCNL4xxx series, with varying ranges and prices</b>. While the sensors look and sound similar, the firmware for these chips is not identical, so you cannot swap the VCNL4030 for VCNL4040 or others without recompiling with the respective libraries!

The VCNL4030 has a nice set of configuration knobs that let you tweak both the proximity sensor (PS) and light sensor (ALS) - for example integration time, dynamic range and sensitivity. Higher integration times mean slower conversion but you can measure dimmer light more precisely. Conversely shorter times mean fast conversion, and can measure brighter lights without oversaturating the sensor. For proximity you can also set up the duty cycle and built-in IR LED current. This lets you balance conversion speed, measurement range, precision and power usage as necessary.

To make life easier so you can focus on your important work, we've taken the VCNL4030 and put it onto a breakout PCB along with support circuitry to let you use this little wonder with 3.3V (Feather/Raspberry Pi) or 5V (Arduino/ Metro328) logic levels. Additionally since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included [SparkFun qwiic](https://www.sparkfun.com/qwiic) compatible [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) connectors for the I2C bus so you don't even need to solder! [Just wire up to your favorite micro and you can use our CircuitPython/Python or Arduino drivers to easily interface with the VCNL4030](https://github.com/adafruit/?q=vcnl4030&type=all&language=&sort=) and make approximate approximations of proximity in no time! [QT Cable is not included, but we have a variety in the shop](https://www.adafruit.com/?q=stemma+qt+cable&sort=BestMatch). 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
