# logisim-iitd
https://sourceforge.net/projects/logisim-iitd/

Logisim is an educational tool for designing and simulating digital logic circuits. With its simple toolbar interface and simulation of circuits as you build them, it is simple enough to facilitate learning the most basic concepts related to logic circuits. With the capacity to build larger circuits from smaller subcircuits, and performing decimal as well as floating point calculations, Logisim can be used to design and simulate entire CPU's for educational purposes.

Originally created BY C. Burch, we have adopted Georgia tech's version of Logisim and integrated the Floating-Point Components within the Arithmetic Unit. Since the earlier version could be used only for integer numbers, this new Logisim-IITD can be used to do arithmetic operations even for IEEE-754 single precision floating point numbers with the help of functions like:

* `FPAdder`: Adds two Floating point numbers. 
* `FPSubtractor`: Subtracts two FP numbers. 
* `FPMultiplier`: Multiplies two FP numbers. 
* `FPDivider`: Divides two FP numbers. 
* `FPComparator`: Compares two FP numbers. 
* `FPNegator`: Negates a FP number. 
* `BinToFP`: Converts a binary number to its corresponding IEEE-754 single precision Floating Point number. 
* `FPToBin`: Converts an FP number to its decimal format.

This new version is used by the students in IIT Delhi and other universities as a part of their curriculum.
