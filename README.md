# cura-and-slic3r-profile
This is my cura and Slic3r settings that I've found to be great on my own 3d printer

## Cura profile/setting
This setting is primarily intended for flow/extrusion multiplier calibration
which turned out to be much better compared to the one from solidoodle's flow
calibration guide and more accurate printing without the risk of under-extrusion

The calculation upon finding the exact/estimated extrusion multiplier would be as follows:

Multiplier = Target wall thickness / Measured wall thickness

E.g, 

Target = 1.2 mm
Measured = 1.4 mm 

0.85714 = 1.2mm / 1.4mm

## Slic3r Settings
This is the main slicer that I use and there are few profiles that I tried with.
The one that I always use is "Balanced" and if your printer is the same as mine
then you can use the profile bundle without much modifications. 

If you're using your own custom g-code, do not forget to change them in the printer
settings according to your liking

Do a backup first before applying my own settings that I've always use
