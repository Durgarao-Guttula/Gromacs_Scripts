# Gromacs_Scripts
This repository creates GROMACS scripts for the tutorials offered by bevanlab (http://www.bevanlab.biochem.vt.edu/Pages/Personal/justin/gmx-tutorials/) .
The Lysosyme tutorial provided by bevanlab is achieved using shell script (tut1.sh) and also implemented for servers using PBS directives (tut.pbs)
To use this script on some other pdb file just change the filename to the name of the file without ".pdb" . This creates the gromacs files strating 
with the pdb filename. This script automatically finds the charge of the system from the topol.top file and adds the appropriate negative or positive 
ion into the solution. The ".txt" files are used to command which type of potential to use or what kind of graph to print. The ".mdp" files used here are downloaded from bevanlab tutorials.

Also changte the command for loading gromacs depending on you system. If you have a serial system please change gmx_mpi to gmx or whatever is suitable.
