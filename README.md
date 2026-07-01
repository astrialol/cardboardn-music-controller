# cardboardn-music-controller
Welcome to my repository. This is a repository that is complete with all of the materials that you need to create a pop'n music controller made out of cardboard using the Arduino Leonardo. It is licensed under GNU General Public License v3 so everyone can have the freedom of relatively cheap-ish DIY.

The ASC can be plugged in via a USB-C or Micro-USB cable (depending on what cable came with your Arduino Leonardo/is compatible with it) to work with your PC.

Before you go into this project, be ready to come up with your own solutions if things ever go wrong.

I'd like to give credit to CrazyRedMachine and his repositories for making this all possible.

https://github.com/CrazyRedMachine/PopnPanel

https://github.com/CrazyRedMachine
## Materials needed
- 22 AWG Stranded Wire: For my build, I used about 5ft perfectly with no wire left over. The max that you'd probably need is 7ft, but I'd say 10ft just to be sure.
- 22 AWG Female to Female Jumpers: These are used to connect the stranded wires to the Arduino. 10 of these are used MINIMUM: 9 for the buttons, 1 for the GND daisy chain. If you'd like Test and Service buttons, you need 12. The length shouldn't matter, but you shouldn't buy something like 5ft as that's unreasonable. Generally buy short jumpers.
- Lever lock connectors w/ at least 3 ports: This is mainly used in the GND daisy chain. It is also used for the connection between the stranded wire & jumpers. I found that transparent connectors were easier to use, but non-transparent connectors work as well.
- Arduino Leonardo or any compatible clone with same pinout and based on ATmega32u4: Brains of the operation. Make sure the clone supports Leonardo code.
- At least 9x 100mm dome buttons for main gameplay buttons [(rhythm-cons has a good list for that; click here if you'd also like test/service buttons)](https://rhythm-cons.wiki/controllers/pop-n-music/pop-n-music/#buttons). If you do buy test/service buttons, I do not cover wiring it up to the arduino. You will have to refer to the [pinout](https://github.com/CrazyRedMachine/UltimatePopnController/blob/master/pinout_leonardo.png) and [dimensions](https://github.com/CrazyRedMachine/PopnPanel#appendix-arcade-accurate-dimensions) if you'd like to DIY.
- Hot glue (5 sticks max will do): To glue in the supports, hot glue will be used. 
- Recommended cardboard dimensions (any longer, wider, or taller box would work): (L: 27.5in, W: 12in, H: 5in)
- Crimping tool, wire cutter, box cutter (only for the box route): Self explanatory.
- Safety goggles (hot gluing), gloves: Safety measures.


## Prepping ##
**Firmware:**
The firmware takes advantage of CrazyRedMachine's code called [UltimatePopnController](https://github.com/CrazyRedMachine/UltimatePopnController). You will also need an Arduino IDE (preferably the Legacy IDE 1.8.19, accessible by going to the [Arduino website](https://www.arduino.cc/en/software/) and scrolling down 'till you see the Legacy IDE button. After downloading and setting it up, you will use this IDE to flash the firmware to the microcontroller itself.

**Case:**
Up to this point, you need to choose one of two paths. Both of them will use [this Github repository by CrazyRedMachine](https://github.com/CrazyRedMachine/PopnPanel). Either make a case out of cardboard / DIY your own case using the dimensions or go to a wood cutting service and submit the files to them. Below are the pros and cons of each option.

<u>**Cardboard/DIY**</u>

+Easier to modify

+You're in control of the size

+Overall cheaper

-Less sturdy

-Needs supports

-Have to cut out holes (this will take long depending on what cutting tools you have available)

<u>**Buying a case**</u>

+Less work

+No supports needed

+More sturdy

-More expensive

-Harder to mod

You can still follow along the guide if you choose to buy a case, but just know that this was mainly designed for cardboard/DIY cases (as I used cardboard for this). The steps should be the same/close to the original.

After everything is prepped, proceed to building.md
