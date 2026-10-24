# About This Fork

This fork adapts Quisk to my own needs, mainly using it as a panadapter for a Xiegu G90, and I'm very grateful to Jim Ahlstrom for this wonderful project.
The changes were made with heavy use of AI, so I don't expect them to be merged upstream, but I'm sharing them in case anyone else wants to do something similar.

Changes:
- Fixed asymmetric mouse wheel tuning (e.g. with Logitech mice, scrolling down jumped twice as far as scrolling up).
- Zoom keeps the waterfall brightness and noise level stable instead of shifting with the zoom level.
- Zoom no longer wipes the waterfall; existing history is rescaled to the new zoom level.
- The mouse wheel moves the Ys, Yz, Zo and Rit sliders in fine single steps.
- New option `waterfall_height_percent` (default 80) sets the waterfall height in the spectrum/waterfall split.

# Quisk Software Defined Radio

Quisk is a software defined radio transceiver that runs on a PC or on a single board computer such as a Raspberry Pi.
It is written in Python and C.
It works with various kinds of radio hardware such as SoftRock, Hermes Lite 2,
the SDR-IQ by RfSpace, and with network UDP samples.
Quisk is easily extensible by writing your own hardware file in Python.

I wrote Quisk back in 2008, and I have been maintaining it ever since.
For questions and support, please visit the group https://groups.io/g/n2adr-sdr.

For more information see https://james.ahlstrom.name/quisk.
