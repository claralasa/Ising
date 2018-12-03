# Ising
Ising simulation for first neightbourhoods using JAVA.

To compile in linux:
> javac Ising.java

To execute:
> java Ising

While executing, the program will ask you for some values:
* System size
  The system side length (square lattice, total L^2)
  
* Reduced temperature (T/Tc)
  The reduced temperature. Separator is a comma (,)
  
* Maximum number of MC Steps (Mcsmax):
  The maximun number of steps of simulation to obtain the state of the system
  
* Use for average every (Ndelta) steps:
  How many steps in order to show data  
  
* Neglect first (Nequil) steps for thermalization:
  In order to obtain the average, how many steps are ignored

* External magnetic field, H:
  The extern magnetic field applied.

If you want to use a custom file with the configuration and set the output to a file, you can use linux command line syntax:
> java Ising < input_file > output_file

Source code at Ising.java

https://github.com/pelusanchez/Ising/


@authors:  Clara Lasaosa García, David Iglesias Sánchez and Lucía Abascal Ceruti
