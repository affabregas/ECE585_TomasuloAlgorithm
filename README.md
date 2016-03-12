# ECE585_TomasuloAlgorithm
##C++ Tomasulo Algorithm Simulator
**Author:   Arthur J. Miller**

Full project can be found on www.github.com/milleraj66/ECE585_TomasuloAlgorithm

Date: 03-11-2016
 
This program has been tested for the given example with several differnt reservation station architectures


#INSTRUCTIONS FOR USE OF THIS PROGRAM:
1. SETUP:

 a. Define the constants for the # of Reservation Stations 
 
 b. initialze Reservation Station objects

 c. Define latency's
 
2. INIT PROGRAM:

 a.Input the MIPS like instructions to your given program 
  
  Ex. ADD F1,F2,F3 // rd <- rs + rt
 
3. RUN

 a. compile using makefile with "make all"
 
 b. run program
 
4. OUTPUT:

 a. Displays the register content of each clock cycle
 
 b. Displays the timing of the ISSUE EXECUTE WRITEBACK at each clock cycle
 

###This program follows the algorithm as stated by the following sources;
1. Computer Architecture : A Quantitative Approach (5th Edition) by Hennessy, John L., Patterson, David A.
2. https://en.wikipedia.org/wiki/Tomasulo_algorithm#Implementation_concepts
3. Dr. Chandra CPP



 