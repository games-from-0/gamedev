# Monday 2nd December

## Compiler
   - Compiling code goes like this: cl [your file]
   - This will create the .exe file (basically your program)

## Debugger
   - This program allows you to step through your code line by line

## Switches
   - To compile code in a certain way, you can give the compiler some options, called "switches"
   - To compile code with these switches, write: cl [your switches one by one] [your file]
   - For example: cl /Zi first_program.cpp
   - The "/Zi" switch basically tells the compiler to produce extra information for the debugger to read (so that the debugger can know which binary instructions correspond to which lines of code, etc...). When specified the /Zi switch, files such as .pdb and .ilk files will get created

