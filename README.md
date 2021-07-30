# PinHP-assets
Collection of assets for AdvanceMame (MAME 0.106), specifically for use in PinHP distribution for Pi2Jamma

## Usage
Put these folders in the rpi2jamma directory and they will be used by the PinHP frontend and Mame

- **artwork_advmame** - some older games had artwork in the cabinet which was projected into the screen and is not part of the roms, these files add that artwork back into the emulator. Try it with Asteroids! Files sourced from here: https://mrdo.mameworld.info/old_artwork.php
- **buttons** - in PinHP mame settings, enable 'Display button layout', enjoy seeing control panel image before game starts. These have been generated using CPWizard, more info on that can be found here: https://github.com/AndyHazz/controls.xml-with-extra-buttons
- **logos** - full set of logo images, all cropped and resized to a standard 140x105px (other logo sets will have random dimensions and don't work so well in frontends that will stretch and squash the images)
- **marquees** - full set of marquees, resized for PinHP's Horizontal Maxi theme layout
- **samples_advmame** - audio samples, provides extra sound effects for games where anaologue or hard to emulate sounds were used - essential for Space Invaders and Donkey Kong! - mostly sourced from https://samples.mameworld.info/
- **snaps** - full set of Mame 0.106 snaps - originally sourced from https://www.progettosnaps.net/oldset/
- **titles** - full set of title screen images, not currently used by PinHP directly, but if you prefer these you can put them in your snaps directory instead of the in-game snaps - also originally sourced from https://www.progettosnaps.net/oldset/
