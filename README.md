# AS5048B Breakout

![board images](Project%20Outputs%20for%20AS5048B_Breakout/boards.png)

This is a simple breakout PCB for the [AS5048B](http://ams.com/eng/Products/Magnetic-Position-Sensors/Angle-Position-On-Axis/AS5048B) 14-bit absolute magnetic encoder.

**Features:**
- Two identical 4-pin JST-PH I<sup>2</sup>C connectors for easy daisy chaining
 - Pin & footprint compatible with [Seeedstudio Grove connectors](http://www.robotshop.com/en/seeedstudio-grove-90-degree-4-pin-connector.html)
- Solder jumpers for setting the A2 & A1 bits in the AS5048B's slave address
- Three M3 mounting holes spaced around a 0.71" (18mm) circle
- Optional LED indicator for debugging connection issues

This board was used in (though not specifically designed for) leg control for an [RHex-style hexapedal robot](https://github.com/brentyi/sparky_firmware) we developed.
