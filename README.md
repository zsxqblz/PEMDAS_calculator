This program is written in ARM assembly. It takes in a series of arithmetic operations as input, and it will perform the calculation. Finally, this program will return the result of the input operations to the user.
If the user inputs an invalid character, this program will return a segment fault.

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