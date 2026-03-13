# HMSIN
A tool for HP-41

This is a program developed for the HP-41 to make it easier to enter a time: hour:minutes:seconds. 

The program is written in MCODE and is therefore particularly fast. It validates the input and stores a time in register X that is compatible with the functions of the TIME module or the HP-41CX.

Once the programme has been entered, simply type 

<code>XEQ HMSIN </code>
<br>
<code>HMSIN: _</code>

and enter HHMMSS in turn; the colons are generated automatically. 
The backspace key deletes the last digit.
Pressing the dot key ends the entry and the time value is stored in X register.
When the command is executed in program mode, pressing the R/S key saves the time in X register and the program continues.
