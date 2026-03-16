# HMSIN
A tool for HP-41

This program is developed for the HP-41 to make entering a time easier. Input time is in format <code>HH:MM:SS</code> where HH is hour, MM are minutes, SS are seconds. HH can be in range 00 - 23 (hr). 

The program is written in MCODE and is therefore particularly fast. It validates the input and stores a time in register X that is compatible with the functions of the TIME module or the HP-41CX.

Once the program has been entered, simply type 

<code>XEQ HMSIN </code>
<br>
<code>HMSIN: _</code>

and enter HHMMSS; the colons are generated automatically to display <code>HH:MM:SS</code> 
Pressing the backspace key <code><-</code> deletes the last digit.
Pressing the dot key ends the entry and the time value is stored in X register.
When the command is executed in program mode, pressing the R/S key saves the time in X register and the program continues.
