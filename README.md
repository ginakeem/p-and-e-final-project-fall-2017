# Interactive Cloud Light

A cloud light made up of neopixels can be turned on by touching the wire. It cycles through different light patterns. 

## Summary

For my final project I coded different light patterns into a neopixel led strip. I originally wanted to make it interactive so that it would change light modes everytime the sensor is touched. The light starts in an off state and when the wire is touched, it turns on and cycles through the light patterns. 

I struggled with finding and modifying code for the neopixels because I had no prior knowledge in how to make them work. I had to do a lot of resesarch to find what functions did what and how to modify existing code. I mostly experimented with color, speed, and how many leds were on at a time. In addition, the touch sensor was difficult because the code did not work with what I was already working with.

## Component Parts

- Adafruit 30 led neopixel strip
- Arduino Uno
- Breadboard
- Wires
- Cotton

The input was a wire where users can touch and turn on the light. The wire is directly connected to pin 3. There is a resistor between pin 2 and 3.

The output is the light. The light is connected to pin 6.

All the wiring was connected through the Arduino Uno and breadboard.

The exterior of the light is cotton. This diffuses the light and makes the light look more appealing. 

## Challenges

The code for  neopixels was difficult at first because I had to learn the new code. I had to research and how different lines of code would affect the lights. I eventually created some code and modified existing code to help fit the patterns I was going for. 

The touch sensor was also a challenge because the code didn't work for me originally. I had trouble finding the correct lines of code and putting them in the right places. My wiring was also slightly off at first, but I fixed it and made it easier by using the breadboard. There were extra wires involved but the breadboard made it easy to follow the flow of the wires.

## Timeline

What did you do in each of the past five weeks?

- Week 1: Write proposal
- Week 2: Buy supplies: neopixels, cotton.
- Week 3: Solder wires onto neopixels, research adafruit neopixel code, begin coding.
- Week 4: Modify code: change color, speed, frequency, etc. Added different color patterns. Experiment with touch sensor.
- Week 5: Add touch sensor, present!

## Completed Work

(Check repository)

## References and links

- http://www.instructables.com/id/Programmable-LED-Firefly-Jar/ 
- http://www.instructables.com/id/Interactive-Ambient-Light/ 
- http://www.instructables.com/id/Interactive-Geodesic-LED-Dome/ 
- http://www.instructables.com/id/Interactive-Thunder-and-Lightning-Cloud/ 
- http://www.instructables.com/id/Jar-of-Fireflies/ 
- https://www.tweaking4all.com/hardware/arduino/adruino-led-strip-effects/
- https://github.com/danasf/attiny_pixel_switch/blob/master/attiny_pixel_touch.ino
- https://github.com/moderndevice/CapSense/blob/master/Examples/CapTouch/CapTouch.ino
- http://www.instructables.com/id/Magic-Light-Capacitance-Sensor-first-ardino-proj/
- https://playground.arduino.cc/Main/CapacitiveSensor?from=Main.CapSense
