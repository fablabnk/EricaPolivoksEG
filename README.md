# Build Notes

- 2N3094 and 2N3096 have been abbreviated to 4 and 6 respectively
- only place NU 39K resistor if requiring -5V ... +5V output on INV EG OUT (presume otherwise get 0-10V)


# TODO

- do not mix NPN and PNP! what is used in original design?
check which DPDT footprint and remove "not verified" from layout
no + - on TL074's in original schematic! Follow pin numbers!
are jacks switched/normalled?
redo BOM - check we have 2.7k resistor! No, just 2.9K

DONE: check diameter of radial caps
DONE: removed TP labels from schematic, can only presume they are useless!
DONE: removed pro power features: polyfuses, reverse polarity protection and inductors
DONE: LED orientation check
DONE: replaced R38 with 2,7k resistor. When 2.2 used and EG OUT is connected to certain VCAs, the looping may stop