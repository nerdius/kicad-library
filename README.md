# KiCad library

##### Here you can find some KiCad library components created by me. Everything is available under the [MIT License](https://github.com/giogziro95/kicad-library/blob/master/LICENSE); you're free to use or modify my work, but if you distribute your own work (either EDA projects or modified versions of the libraries) that uses libraries or other files from this repo, you should credit me as stated in the license.

## Libraries

### [Eeschema](https://github.com/giogziro95/kicad-library/tree/master/eeschema)

#### Components

**Here's the list of components included in the _misc_giogziro95.lib_ library file:**

* 7405 (6-bit buffer / line driver; inverting)
* 74141 (BCD to decimal decoder/driver; active-high outputs)
* AC110V (110V/60Hz AC power source)
* AC220V (220V/50Hz AC power source)
* AC_custom (AC power source; customizable label)
* Arduino_Nano_R3 (Arduino Nano, a programmable single-board microcontroller based on ATmega328)
* Arduino_Uno_R3 (Arduino Uno, a programmable single-board microcontroller based on ATmega328P)
* FSR (Force-sensitive resistor)
* HX711_module (24-bit analog-to-digital converter for weigh scales)
* Load_cell (4-wire load cell for weigh scales)
* Wheatstone_bridge (Wheatstone bridge)

#### Using

**To use a library, after you clone the repo using Git (or download and extract the archive):**

1. Go to KiCad and load Eeschema.
2. Go to _Preferences_ → _Component Libraries_.
3. Click _Add_ under _Component library files_, then locate and and select the desired library file. (Alternatively, you can click another _Add_ under _User defined search path_ and select your project directory and then drop the library file there. This one is convinient when you use multiple libraries and you don't want to deal with adding them individually.)
4. Click OK.
5. Now you can place the components from this library.

**If you want to import an individual symbol into an already existing library instead, you can do the following:**

1. Go to KiCad and load the schmatic library editor.
2. Select your working library and create a new component in there.
3. Click the _inport exixting drawings_ button on the right toolbar.
4. Do some final edits, tweaks, and customizations of properties, etc.
5. Save the library and confirm your changes.

**Note:** You can also import a symbol within an existing component. To do that, just substitute the second step with selecting the library and loading a component.  
**Note 2:** If you just want to use a component from this library, it's highly recommended if you use the entire library rather than the individual components; it's time-saving and it automatically imports all the layouts, properties, descriptions, aliases and keywords of the components, so you don't need to re-edit and -tweak them.

**<p align="center">Happy designing!</p>**
