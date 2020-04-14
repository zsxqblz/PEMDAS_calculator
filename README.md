This program is written purely in ARMv7 assembly. It takes in a series of arithmetic operations as input, and it will perform the calculation and print the result. It supports arbitary operations order 
following the PEMDAS rule: Parenthesis > Multiplication > Division > Addition > Subtraction. Exponential is not supported. Both integer and float point operations are supported.
If the user inputs an invalid character, this program will return a segmentation fault.

The code is developed as my final project of ECE251 at Cooper Union

To build it:
1. in a shell cd to this directory
2. type either 
    make
or
    gcc -o final final.s -mfpu=vfpv4 
and then press enter
3. you should see a file named final appeared in the same directory

To execute it:
1. in a shell cd to this directory
2. type
    ./final "//put your inputs here//"
and put your inputs in between the quotation marks.
3. Hit enter
4. The result of your input calculation will be shown on your screen.