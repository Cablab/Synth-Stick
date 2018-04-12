# Working-SynthStick

Our project has been tested and is currently working, so all previous file versions have been removed at this point for clean up purposes. Here are the changes made from v4-LCD-pointers:

- Remapped keyBPin to 9 since 4 doubles as a reset and was giving us issues
- Refactored code that checks for button presses into separate function
- Added some needed comments
- Updated getMinorPentNotes with correct values at steps 3 and 4

# Working-SynthStick-v2

Almost the final version of the code, a few changes were made to make the Synth Stick more dynamic and user friendly:

- Inclusion of Minor and Chromatic scale
- Added a button to change key down a step, mapped to pin 1
- Refactored code, especially in keyUp() and keyDown()
- More comments
