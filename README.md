## Adafruit Prop-Maker FeatherWing PCB

<a href="http://www.adafruit.com/products/3988"><img src="assets/3988.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Prop-Maker FeatherWing. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3988

### Description

The Adafruit Feather series gives you lots of options for a small, portable, rechargeable microcontroller board. Perfect for fitting into your next prop build! This FeatherWing will unlock the prop-maker inside all of us, with tons of stuff packed in to make sabers & swords, props, toys, cosplay pieces, and more.

We looked at hundreds of prop builds, and thought about what would make for a great low-cost (but well-designed) add-on for our Feather boards. Here's what we came up with:

 * **Snap-in NeoPixel port** - With a 3-pin JST connector, you can [plug in one of our JST-wired NeoPixel strips directly](https://www.adafruit.com/product/3919), or use a [3-pin JST connector to wire up your favorite shape of addressable NeoPixel LEDs](https://www.adafruit.com/?q=jst%203-pin). This port provides high current drive from either the Feather Lipoly or USB port, whichever is higher. A level shifter gives you a clean voltage signal to reduce glitchiness no matter what chip you're using
 * **3W RGB LED drivers** - 3 high current MOSFETs will let you [connect a 3W RGB LED for powerful eye-blasting glory](https://www.adafruit.com/product/2530). For most Feathers, the 3 pins are PWM capable so you can generate any color you like. Available as pin breakouts plus strain-relief holes
 * **Triple-Axis Accelerometer with Tap Detection** - The LIS3DH is our favorite accelerometer, you can use this for detection motion, tilt or taps. [Here's an example of a light saber that makes sounds when swung or hit](https://learn.adafruit.com/hallowing-lightsaber). We have code for this chip in both Arduino and CircuitPython.
 * **Class D Audio Amplifier** - Drive a 8Ω 1Watt speaker or 4Ω 3W speaker for sound effects. [Plug and play with our cute and slim oval speaker](https://www.adafruit.com/product/3923), or [connect a picoblade cable](https://www.adafruit.com/product/3922) for your favorite speaker. For use only with Feathers that have analog audio out such as the Feather M0 Express and M4 series.
 * **Low power mode!** The power system for the RGB LED, NeoPixels and speaker amplifier can be controlled by a pin to cut power to them, so you have lower power usage when the prop is in sleep or off mode (but can wake up fast by listening to the button press or accelerometer data). When the power pin is set low, the current draw for just the wing is under 1mA and no there's current draw from any attached NeoPixels - normally they're about 1mA even when not lit.
 * Breakouts plus strain-relief hole for the enable pin and ground (for a mechanical switch that will power down the whole board)
 * Breakouts plus strain-relief holes for an external switch pin and ground (for a mechanical mode button)
**Please note**: A few of the onboard hardware elements use PWM and analog output so we recommend the **Feather M0 Express or Feather M4** series, they'll work best with this wing and let you make the most of it. For example:

Feather 32u4 and 328p do not have PWMs for all the RGB LED pins, and no analog audio output support
Feather nRF52, ESP32 ESP8266 do have PWMs on all the RGB LED pins but no analog audio output support
Feather M0 basic boards only have audio output support in Arduino, not CircuitPython.
That doesn't mean you can't use this 'wing with the Feather ESP8266 or nRF52832, just that you won't get any sound effects. You can still use the accelerometer, NeoPixels, RGB LED, etc.

As you can tell, the **M0 Express and M4** series is what we recommend cause you'll get everything and with CircuitPython, its really easy to play audio directly off the built in flash chips!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
