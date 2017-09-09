# KiCad library

##### Here you can find some KiCad component libraries created by me. Everything is available under the [MIT License](https://github.com/giogziro95/kicad-library/blob/master/LICENSE); you're free to use or modify my work, but if you distribute your own work (either EDA projects or modified versions of the libraries) that uses libraries or other files from this repo, you should credit me as stated in the license.

## Libraries

### [Eeschema symbols](https://github.com/giogziro95/kicad-library/tree/master/eeschema)

#### Components

**Here's the list of components included in the _misc_giogziro95.lib_ library file:**

* 7405 (alias: 555ЛН2) (6-bit buffer / line driver; inverting)
* 74141 (alias: 155ИД1) (BCD to decimal decoder/driver; active-high outputs)
* AC-DC_power_supply (AC-to-DC power supply)
* AC_power (AC power source; customizable label)
* Arduino_Nano_R3 (Arduino Nano, a programmable single-board microcontroller based on ATmega328)
* Arduino_Uno_R3 (Arduino Uno, a programmable single-board microcontroller based on ATmega328P)
* DC_power (DC power source; customizable label)
* FSR (Force-sensitive resistor)
* HX711_module (24-bit analog-to-digital converter for weigh scales)
* Load_cell (4-wire load cell for weigh scales)
* Wheatstone_bridge (Wheatstone bridge)

#### Using

**To use a library, after you clone the repo using Git (or download and extract the archive):**

1. Go to KiCad and load Eeschema.
2. Go to _Preferences_ → _Component Libraries_.
3. Click _Add_ under _Component library files_, then locate and and select the desired library file. (Alternatively, you can click another _Add_ under _User defined search path_ and select your project directory and then drop the library file there. This one is convinient when you use multiple libraries and you don't want to deal with adding them individually.)
4. Click _OK_.
5. Now you can place the components from the library.

**If you want to import an individual component into an already existing library instead, you can do the following:**

1. Go to KiCad and load the schmatic library editor.
2. Select your working library.
3. On the top toolbar, click the _Import component_ button.
4. Select for the desired component librery file.
5. If you want to, do some final edits, tweaks, customizations, etc.
6. On the top toolbar, click _Update current component in current library_ button.
7. Save the library and confirm your changes.

**<p align="center">Happy designing!</p>**
