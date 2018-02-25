# IIL logic examples with LTspice

[Integrated injection logic](https://en.wikipedia.org/wiki/Integrated_injection_logic) (IIL, I<sup>2</sup>L or I2L) is a bipolar transistor logic family popular in the 1970s.

## Modules
| File        | Comment                           |
|-------------|-----------------------------------|
| cla1        | carry look ahead unit for bit 1   |
| cla2        | carry look ahead unit for bit 3   |
| cla3        | carry look ahead unit for bit 3   |
| fag0p0      | full-adder with no P/G outputs    |
| fag1p1      | full-adder with 1 P/G outputs     |
| fag2p2      | full-adder with 2 P/G outputs     |
| fag3p3      | full-adder with 3 P/G outputs     |
| iil1        | IIL gate with 1 collector outputs |
| iil2        | IIL gate with 2 collector outputs |
| iil3        | IIL gate with 3 collector outputs |
| iil4        | IIL gate with 4 collector outputs |
| iil5        | IIL gate with 5 collector outputs |
| iilin1      | inverted level-shifter VDD-logic to IIL with 1 collector output |
| iilin2      | inverted level-shifter VDD-logic to IIL with 2 collector outputs |
| iilin3      | inverted level-shifter VDD-logic to IIL with 3 collector outputs |
| iilin4      | inverted level-shifter VDD-logic to IIL with 4 collector outputs |
| iilout      | terminate ILL output              |
| tb_add1     | testbench with 1 digit adder      |
| tb_add4     | testbench with 4 digit adder      |
| tb_count4   | testbench with 4 digit adder which increments by one |
| tb_ringosc9 | testbench 9 stage ring-oscillator |
