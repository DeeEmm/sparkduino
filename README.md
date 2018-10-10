Sparkduino
=========

Arduino based engine ignition system forked from Speeduino EFI code. 
The current Sparkduino code is based on the September 2018 Speeduino Release (Speeduino-201808)


What is Sparkduino?
===================

Sparkduino is a user mappable, distributor-less, crank-fired ignition system that can be used on a variety of engine configurations. It will run on the original Speeduino hardware and its derivatives as well as on custom hardware based on the Arduino Mega 2560 processor.

Sparkduino is programmed by using Tuner Studio.


Project Goals
=============

Maintain an up-to-date ignition-only version of the Speeduino code.
Maintain tuner studio ini and dashboard files to provide customised 'ignition only' tuner studio experience

Integrate additional relevent 'ignition only' features that are not currently relevent to Speeduino.


FAQ
===

- Q. What hardware do I use?
- A. You can use any of the current Speeduino boards or its derivatives (check out the user boards in the forum). If building a Speeduino board from a kit you can also elect to not populate the circuitry that relates to the injector drivers. You can also build your own custom board if you desire.

- Q. Whats different from the Speeduino code?
- A. Most of the changes relate to the ini file used by Tuner Studio. Currently the arduino code is the same as Speeduino.

- Q. What additional features are planned? 
- A. The following additional features are currently being considered:
  - Shift light
  - Water / meth injection control



Roadmap
=======

~~- [ ] Remove remaining injector related parameters from Tuner Studio~~
- [x] Create custom ini files for tuner studio
- [ ] Impliment Shift light code along with Tuner Studio Dialogue
- [ ] Impliment Water / Meth control along with Tuner Studio Dialogue


License
=======

Sparkduino is released under the GNU GPL V2 license
