# Four-Bit-Full-Adder
**What does this program do?**

A VHDL program that takes in two binary numbers and calculates the sum in binary.

_This program is intended for use with a Basys3 Board._

**How does it do it?**

With the Basys3 board, 2 binary numbers are taken in using the switches on the bottom of the board. The right-most 4 switches (W17 through V17) represent the first number input, the next 4 switches (W13 through W15) represent the second number input, and the next switch (V2) represents the carry in value. 

If a switch is flipped up or "on" the value is one. If it is flipped down or "off" than the value is zero.

The LEDs (W18 through V16) above the switches represent the sum of the numbers inputted.
