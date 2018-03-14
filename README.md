# FARSI_Serial_3D_TLP
FARSI is fortran code developed to study Fluid And Renewable Structure Interaction (FARSI) problems. The code originally developed to study wave forces on floating wind turbines. It has been used later to study other offshore structures, such as wave energy convertor, monopile and barge. The model uses finite volume approach and explicit method to solve Navier-Stokes equations, level set method for tracking the wave's free surface and immersed boundary method to study solid-fluid interaction.


Following is a step by step procedure for running a code on a linux machine:

1-Install git if it is not already installed. To install git in in ubuntu operating system type "sudo apt-get install git".

2-download FARSI by typing "git clone https://github.com/AliNemat/FARSI_Serial_3D_TLP.git".

3-Install Intel Fortran compiler if it is not already installed. Other compilers can also be used by changing the name of the fortran compiler in the makefile).

4-In the folder "~/FARSI_Serial_3D_TLP" type: "make" to compile the code. An exe file should be generated.

5-type "./TLPDec29H6.4" to run the exe file. Name of the exe file can be changed in the makefile.

6-To visualize the output data "Tecplot" needs to be used (https://www.tecplot.com/).
