# logic-gates-logisim
Examples of Logic Gates using Logisim simulator

## XOR gate 
|X|Y|XOR|
|-|-|-|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

![XOR Gate diagram](./images/XOR%20Gate%20Logisim.png)

[Beginner's tutorial (cburch.com)](http://cburch.com/logisim/docs/2.7/en/html/guide/tutorial/index.html)

[Logisim Beginner's Tutorial (youtube.com)](https://www.youtube.com/watch?v=cMz7wyY_PxE)

## AND, OR, NAND, NOR, XOR, XNOR and half and full Adder gates

![AND, OR, NAND, NOR, XOR, NOR and half and full ADD](./images/AND%20OR%20NAND%20NOR%20XOR%20XNOR%20NOT%20and%20half%20and%20full%20ADD.png)

[Logisim ALU Tutorial (youtube.com)](https://youtu.be/dYZ-Hwbcnq4)

## Half Adder

|IN A|IP B|OP S|OP C|
|-|-|-|-|
|0|0|0|0|
|0|1|1|0|
|1|0|1|0|
|1|1|0|1|

## Full Adder

IP Cin|IP A|IP B|OP S|OP C|
|-|-|-|-|-|
0|0|0|0|0|
0|0|1|1|0|
0|1|0|1|0|
0|1|1|0|1|
1|0|0|1|0|
1|0|1|0|1|
1|1|0|0|1|
1|1|1|1|1|




## Subtraction and Multiplication
![Subtraction and Multiplication](./images/Sub%20and%20Mul.png)


## Subtraction

|IN A|IP B|OP S|OP C|
|-|-|-|-|
|0|0|0|0|
|0|1|1|1|
|1|0|1|0|
|1|1|0|0|

## Multiplication

|IN A|IP B|OP M|
|-|-|-|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

## Comparator
![Comparator](./images/Comparator.png)

The MSB (Most Significant Bit) is reserved for the sign.

|IN A|IP B|>|=|<|
|-|-|-|-|-|
|001|000|1|0|0|
|001|001|0|1|0|
|001|010|0|0|1|
|001|011|0|0|1|
|001|100|1|0|0|
|001|101|1|0|0|
|001|110|1|0|0|
|001|111|1|0|0|

## D-type Flip Flop
![D-type Flip Flop](./images/D%20type%20flip%20flop.png)
|D|CLK|Q|-Q|
|-|-|-|-|
|1|1|1|0|
|0|1|0|1|
|X|0|Last state||

## 8-bit Register (1 byte memory)
![8-bit Register (1 byte memory)](./images/Computer%20memory%20using%20flip%20flops.png)
## Decoder
![Decoder](./images/Decoder.png)

|I1|I2|O3|O2|O1|O0|
|-|-|-|-|-|-|
0|	0|	0|	0|	0|	1|
0|	1|	0|	0|	1|	0|
1|	0|	0|	1|	0|	0|
1|	1|	1|	0|	0|0|

## 2 out of 3 logic using gates
Any two inputs should be positive for the output to be positive.
![2 out of 3 logic](./images/2%20out%20of%203%20logic.png)


|A|B|C|A+B|(A+B)*C|AB|(A+B)*C+AB|
|-|-|-|-|-|-|-|
|0|0|0|0|0|0|0|
|0|0|1|0|0|0|0|
|0|1|0|1|0|0|0|
|0|1|1|1|1|0|1|
|1|0|0|1|0|0|0|
|1|0|1|1|1|0|1|
|1|1|0|0|0|1|1|
|1|1|1|0|0|1|1|

## Tri-state buffer/inverter
![Tri-state buffer/inverter](./images/Tri-state%20buffer.png)

### Buffer 

|C|I|O|
|-|-|-|
|0|0|Z|
|0|1|Z|
|1|0|0|
|1|1|1|

### Inverter

|C|I|O|
|-|-|-|
|0|0|Z|
|0|1|Z|
|1|0|1|
|1|1|0|

[Controlled Buffer/Inverter (cburch.com)](http://www.cburch.com/logisim/docs/2.3.0/libs/gates/controlled.html)


