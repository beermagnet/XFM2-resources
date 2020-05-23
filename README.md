# XFM2 resources

*for bringing in comments and/or additions you can post an* **Issue**

## The XFM2

The XFM2 Synthesizer Module is a 64-voice, 2-part, 6-operator FM Synthesizer with built-in effects processor, built on an FPGA chip.
It is the second generation of the XFM DIY Synthesizer Project by René Ceballos.

In short the XFM2 houses 2 independent 32 voice DX7's on steroids with an impressive sound quality.

However next to the possibility to mimic a DX7, the XFM2 is far more sophisticated with more complex modulation and feedback possibilities. If you are in doubt to build one, put a hundred bucks aside and read the manual.

The build is based on two pre-assembled development boards: the Digilent CMOD A7-35T (FPGA, USB, SRAM) and the Adafruit UDA1334A (I2S stereo DAC). 
This combination allows to get the module running in less than 10 components (about $99 total cost).

A user manual, installation guide, and the binaries that have to be loaded into the FPGA – using the provided instructions – are all made available.



[The XFM2 Synthesizer Module](https://www.futur3soundz.com/xfm2)

[Blog by René Ceballos](https://www.futur3soundz.com/da-blog)


The XFM2 is very well documented, but there is no GUI other then a spreadsheet to change parameters and set presets.

Therefore there are some projects started with several solutions to expand the posabilities of the XFM2



## Social

[XFM2 on Gearlutz](https://www.gearslutz.com/board/electronic-music-instruments-and-electronic-music-production/1297008-xfm2-fgpa-based-fm-synth-1.html)

[Slack Channel for XFM2](https://join.slack.com/t/xfm2/shared_invite/zt-dmrs50h3-34WvYiWgPBWruNXSXLYgBg)

## Hard and software projects

### xfm2controller
A controller for the XFM2 Synthesizer using Qt 5.12

- [xfm2controller](https://github.com/ataristdude/xfm2controller)


### A simple Arduino-based XFM2 front panel
an Arduino interface, as minimal as possible (but still user-friendly and useful)

- [XFM2interface](https://github.com/dylanmc/XFM2interface)

### XFM2UI
XFM2UI is an Arduino menu driven user interface for all XFM2 parameters. It is based on Teensy 4.0

- [XFM2UI](https://github.com/mlinton/XFM2UI)

### XFM2_patches
json patch files for the XFM2

-[XFM2_patches](https://github.com/xerhard/XFM2_patches)

### DX7syx-to-XFM2patches
Quick and dirty convertion of DX7 sysex files containing 32 presets into XFM2 json patch files.

- [DX7syx-to-XFM2patches](https://github.com/xerhard/DX7syx-to-XFM2patches)


### XFM2_GetterSetter
small JavaFX application to read/write & text edit XFM2 json patches
- [XFM2_GetterSetter](https://github.com/xerhard/XFM2_GetterSetter)