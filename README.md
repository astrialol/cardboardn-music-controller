# cardboardn-music-controller
Welcome to my repository. This is a repository that is complete with all of the materials that you need to create a pop'n music controller made out of cardboard using the Arduino Leonardo. It is licensed under GNU General Public License v3 so everyone can have the freedom of relatively cheap-ish DIY.

The ASC can be plugged in via a USB-C or Micro-USB cable (depending on what cable came with your Arduino Leonardo/is compatible with it) to work with your PC.

Before you go into this project, be ready to come up with DIY solutions in case you ever 
## Materials needed
- 22 AWG Stranded Wire | 10ft is (i assume) the maximum that you need for this project.
- 22 AWG Solid Wire (only tiny bit is needed; this is used to connect the Arduino to the stranded wire) | 2ft is overkill but the max that you'd need.
- Lever lock connectors w/ at least 3 ports | x18
- Arduino Leonardo or any compatible clone with same pinout and based on ATmega32u4
- At least 9 buttons for main gameplay buttons
- Hot glue (5 sticks max will do)
- You are able to use extra 30mm buttons for test/service buttons, however I did not include that in my controller and unfortunately cannot provide dimensions/directions for those buttons.
- Recommended cardboard dimensions (any longer, wider, or taller box would work): (L: 27.5in, W: 12in, H: 5in)
- Some tools will be required such as:
-- Crimping tool
-- Wire cutter
-- Box cutter (to cut the box; however if you absolutely cannot obtain one, a tiny knife could work. I have not tested if a kitchen knife works so use it at your own discretion. Be careful!)

## Prepping ##
**Firmware**
The firmware takes advantage of CrazyRedMachine's code called [UltimatePopnController](https://github.com/CrazyRedMachine/UltimatePopnController). You will also need an Arduino IDE (preferably the Legacy IDE 1.8.19, accessible by going to the [Arduino website](https://www.arduino.cc/en/software/) and scrolling down 'till you see the Legacy IDE button. After downloading and setting it up, you will use this IDE to flash the firmware to the microcontroller itself.

**Making the case**
You can find approximate dimensions for the spacing between buttons in the "dimensions" folder of this repository. The designs are able to be printed on LTR size paper for added convienience; however ensure that margins are disabled and size is accurate. Double-check after printing by measure with a ruler.


