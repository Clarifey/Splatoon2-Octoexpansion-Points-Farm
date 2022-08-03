# Splatoon2-Octoexpansion-Points-Farm

Its go in a Level and then Farm Points.

What you need:
1.An Arduino Leonardo or other Micro Controller with an atmega32u4 chip.
2.Two Wires Male to Male
3.Micro Usb Cable
4.Pc or Laptop
5.A Nintendo Switch
---

How to setup. 

Make in the directory a new folder with the Name lufa and download this file from here:https://github.com/abcminiuser/lufa/tree/597fbf47cd2551423a231ac747e2f1405cf9306a
and put them in the lufa folder.

First open a Terminal and go to the Splatoon2-Octoexpansion-Points-Farm directory,run:
```
make
```
After thath Plug your Arduino in youre Pc and One Wire in an Ground pin and the other Wire in the Reset pin and Short the together now look in the device manager wich COM pops up and put the number in the command after COM and run it:
```
avrdude -v -patmega32u4 -cavr109 -PCOM -Uflash:w:Joystick.hex
```
In Splatoon2 in the normal Lobby press plus and go to the settings and change the right stick Sensy to 0.

After thath go in octo expansion in the grey line and play the Level DO2 with the two snipers.

And After thath plug the arduino in when you in the normal Octo Expansion Underground Bahn dont press anthing on your controller.

Have Fun with it if any Problem or Question ask me.

#### Thanks

Thanks to https://github.com/CraftyDuck100/woff-grinder i used it to make the Splatoon 2 Farm Script.

Thanks to https://github.com/bertrandom/snowball-thrower for the updated information which modifies the original script to throw snowballs in Zelda. This C Source is much easier to start from, and has a nice object interface for creating new command sequences.

Thanks to Shiny Quagsire for his [Splatoon post printer](https://github.com/shinyquagsire23/Switch-Fightstick) and progmem for his [original discovery](https://github.com/progmem/Switch-Fightstick).
