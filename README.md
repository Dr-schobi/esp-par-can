# WLED in a LED PAR can 

For my Halloween decoration, I wanted to have some colored lights. 
I went with cheap LED PAR can lights.
However, out of the box those are pretty limited. 
At most, you can type in a color with the pushbuttons on the back.
Anything more requires the setup of a DMX controller and wiring.

## THomann Fun Generation USB PartyPar 6 RGB

For 13.50€ Thomann in Germany sells a basic colored light - this light is as basic as you can get. 
It has RGB with 5W max and only three modes (fade, automatic, sound), so not even an adjustment if you want green light.
Pretty useless if you want to ge beyond blinky-blink? no!

Advantages:
Passive LED module, with a USB power supply with USB-C cable (5V 1A), and plenty of space in the housing.

I need to give Mario all the credit, see [](https://protyposis.net/blog/rgb-led-party-spotlight-wled-upgrade/)

Plan:
Replace the STM microcontroller with a WLED on ESP32 module. Surprisingly, WLED can output multiple PWM signals in the regular firmware.
In the end you will have a single pixel LED fixture that can be controlled with WLED.


