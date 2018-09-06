1)KNOWELS MIC

-Added test points and gnd scatter with thermal vias.
-Removed regulator ,reverse protection diode and provided (5.1 volts) zener diode.

2)SIM5320e

-Checked pullup,pulldown and leave open for all pins in main IC.

-I2C pins have internaly pulled up with a (2.2K R) to 2.6V internally. So,it recomended to keep open if unused.

-For SPI datasheet show if unused keep open and doen't give anything for if use condition.


3)SDCARD

-Don't have any changes

4)serial_to_FDTI

-Removed micro usb and replaced USB_type_A

5)MEMS MIC and SD CARD integration.

-Sperated Analog and digital ground ,Provided back to back schotkey diode.

6) I have added respective 3D Models of the board in seprate forlder ,View using sketch_up.
