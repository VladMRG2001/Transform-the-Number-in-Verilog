# Transform the Number in Verilog

## Objectives
The project aims to familiarize students with the basics of Verilog programming, including: <br>
-> Dividing a general problem into specific functional modules. <br>
-> Implementing a given algorithm in a synthesizable manner. <br>
-> Creating a finite state machine (FSM) based on a provided diagram. <br>

## Description and Requirements
-> Implement a finite state machine in Verilog to convert a number from base 2 to base 3. <br>
-> The circuit will accept a binary number input along with an enable signal. <br>
-> The output will be the number in base 3, accompanied by a validation signal (done). <br>
-> The conversion algorithm involves repeated division and remainder calculation, favoring an FSM design that calls a secondary module for division. <br>

## Implementation
The solution is split into two distinct modules with specific functionalities: <br>
-> 1. **base2_to_base3**: Main module implementing the FSM for conversion. <br>
-> 2. **div_algo**: Module performing division and remainder calculation for two 16-bit natural numbers. <br>

## Example
For the input base2_no = 58, the conversion algorithm is illustrated through repeated division and storing remainders, resulting in the output base3_no = 32'b0000_0000_0000_0000_0000_0000_1000_0101.
