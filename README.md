# DnD-Tracker
Repository for my resource tracker for D&amp;D
The premise of this project is to make keeping track of health, spell slots, and other resources quick and simple,
while preserving the vibe of an ttrpg.
It consists of 3 modules. One, keeps track of your health (3 led strips each one representing one digit of a 3 digit number)
Second one keeps track of your spell slots
The last one keeps track of whatever 20 resources you have, potions class features, magic items etc.
The rgb leds are driven by a 555 timer based circuit, this allows for controlling the color and brightness of the lights.
A standard 18650 cell is enough to power it for tens of hours (depending on the brightness level)
This project is not yet fully finished, the pcb and the files contain some errors that I haven't fixed yet.
The errors are:
  - Didn't reverse the logic of the LED ON button, insead of turning the leds off, it blasts them at full power
  - The housing has misaligned mounting holes
## The Future
I might make the design modular, this would enable greater flexibility and probably would be cheaper.
Making the housing more practical and prettier.
