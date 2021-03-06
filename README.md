# Programmable Colloidal Particles Simulator
<img src="https://github.com/hidetana18/Programmable-Colloidal-Particles-Simulator/blob/master/Images/repli.gif" width="400">

## 1. Introduction

### `C-files`

Codes written in C for Molecular Dynamics simulation of Brownian particles with programmable "specific" and "dynamic" inter-particle interactions. (e.g. DNA colloids) You can assign distinct "species" for each particle and define "interaction matrix" to characterize time-dependent inter-particle interactions among them.   

`main.h`: Declare various constants and functions to be used   
`func.c`: Define functions   
`main.c`: Put the functions together to complete iterations 

<img src="https://github.com/hidetana18/Programmable-Colloidal-Particles-Simulator/blob/master/Images/SelfRepScheme.jpeg" width="500">


### `PyAnalysis`

Python codes in Jupyter notebooks for data analysis and visualization. 
Main figures presented in the above paper are reproduced.


## 2. Basic Usage
Main Brownian Dynamics simulation codes in `C-files` can be compiled with `makefile`.
While running, it outputs trajectory of all particles `traj---.dat` and number of self-replicated clusters with each species `NumCl---.dat`. Examples of data analysis and visualization using the output data are presented in the Jupyter notebook.



## 3. Summary of the research
Rapid developments in DNA nanotechnology opened up the new paradigm of "programmable materials" in nano/micron scales. The  DNA mediated "specific" and "dynamic" inter-particle interactions are hard to implement with existing molecular dynamics libraries. To explore the design space, and investigate possibilities for realizing self-replicating artificial living materials, I have developed this molecular dynamics simulation that implements the above self-replication scheme. Finally, this highly efficient codes allowed us to observe hundreds of self-replicating colloidal clusters, and thus we conducted the first study of "evolutionary dynamics" of artificial materials.

<img src="https://github.com/hidetana18/Programmable-Colloidal-Particles-Simulator/blob/master/Images/Col_meet_Bac.001.jpeg" width="500">



Part of this repository presents codes written by Hidenori Tanaka for     
H. Tanaka, Z. Zeravcic, M.P. Brenner “Mutation at Expanding Front of Self-Replicating Colloidal Clusters.”     
[Physical Review Letters, 117, 238004, (2016).](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.117.238004)
