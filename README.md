Sparkduino
=========

Arduino based engine ignition system forked from Speeduino EFI code.


What is Sparkduino?
===================

Sparkduino is a user mappable, distributor-less, crank-fired ignition system that can be used on a variety of engine configurations. It will run on the original Speeduino hardware and its derivatives as well as on custom hardware based on the Arduino Mega 2560 processor.


Project Goals
=============

The main goal of the project is to maintain an up-to-date ignition-only version of the Speeduino code so that those of use who run ignition-only systems can use a simplified and more relevent version of Tuner Studio.

Additional features may also be integrated into the software


FAQ
===

Q. Whats different from the Speeduino code?
A. Most of the changes relate to the ini file used by Tuner Studio. The injector related parameters and dialogues have been removed leaving only the ignition parameters. The software uses a different code signature to differentiate it from the Speeduino code it is based on. 

There are also some additional features planned that currently fall outside of the current Speeduino road map.

Q. What additional features are planned?
A. The following additional features are currently being considered:
  - Shift light
  - Water / meth injection control


Roadmap
=======

- Remove remaining injector related parameters from Tuner Studio
- Impliment Shift light code along with Tuner Studio Dialogue
- Impliment Water / Meth control along with Tuner Studio Dialogue


License
=======

Sparkduino is released under the GNU GPL V2 license
