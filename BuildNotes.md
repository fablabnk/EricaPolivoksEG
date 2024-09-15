# V1.0

## Things to pay attention to whilst building
- solder "G.Delay Out" jack socket before 100k resistor 
- ms202 switch should probably be wired before 3.3k and 1p0m resistors that are within its footprint

## Design issues to fix in V1.1
- just put A or B instead of log or lin on pot silkscreening
- footprints too wide for 104 caps
- widen switch panel hole to at least 6mm
- TL074 silkscreen text should be outside of footprint so it can be seen after socket is installed

## Component issues
- 100k resistors don't even measure close to 100k (80-85) and 560k resistors don't even measure close to 560k. This seems to be down to an issue with lab multimeters. The one with croc clips measures correctly
- need to place 39K resistor marked NU or not? No, NU means 'not used'. Placing this resistor would change output from standard 0 to 10V to -5V to 5V (I think...or vice versa?)
