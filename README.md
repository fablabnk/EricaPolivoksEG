# Build Notes

- 2N3094 and 2N3096 have been abbreviated to 4 and 6 respectively on silkscreeningg
- only place NU 39K resistor if requiring -5V ... +5V output on INV EG OUT (presume otherwise get 0-10V)

# TODO

check which DPDT footprint and remove "not verified" from layout
DONE: check IDC power pins & keying - stripe should be to -12V rail
DONE: check inverting (-) and non-inverting inputs (+) on TL074 in schematic by comparing to pinout
DONE: redo BOM - check we have 2.7k resistor! No, just 2.9K
DONE: are jacks switched/normalled? Yes pin 3 is engaged instead of pin 2 when the jack in unplugged
DONE: do not mix NPN (2N3904) and PNP (2N3906)
DONE: check diameter of radial caps
DONE: removed TP labels from schematic, can only presume they are useless!
DONE: removed pro power features: polyfuses, reverse polarity protection and inductors
DONE: LED orientation check
DONE: replaced R38 with 2,7k resistor. When 2.2 used and EG OUT is connected to certain VCAs, the looping may stop