#########################################
####        Abhiram B R		     ####	
#### Department of Civil Engineering ####
####  Indian Institute of Science    #### 
####     abhirambr@iisc.ac.in 	     ####	
#########################################

If you use this code in any future publications, please cite the following publications:

1. Abhiram B R and Debraj Ghosh, Atomic investigation on optimal interfacial bonding for enhanced fracture properties in polymer nanocomposites, Engineering Fracture Mechanics (2023): 109078
2. Abhiram B R and Debraj Ghosh, Influence of nanofiller agglomeration on fracture properties of polymer nanocomposite: Insights from atomistic simulation, Engineering Fracture Mechanics (2023): 109503

------------------------------------------------------------------------------------------------------------------------------------------------------------------

This folder contains molecular dynamics (MD) codes to simulate the influence of varying degrees of functionalization on the
fracture properties of polymer nanocomposites (PNC).
Modeling is performed in Materials Studio 6.0
The model is then imported to LAMMPS using msi2lmp tool
All MD simulations are performed in LAMMPS and the post-processing is performed using OVITO and MATLAB

------------------------------------------------------------------------------------------------------------------------------------------------------------------

The directory includes the following folders and files

Folder names:
3.5_percentage	- consists of MD code and dependent files for simulating fracture properties of PNC with 3.5% functionalizaed CNT reinforcement
10_percentage, 15_percentage, 20_percentage, 30_percentage and 40_percentage - consists of similar codes with varying degrees of functionalization
Subdirectoy names:
equilibration   - MD code for running sequence of equilibration
tension		- MD code for running uniaxial tension boundary condition

File names:

in.equi_pmma_pnc_funct	- MD code to simulate equilibration of PNC
in.pnc_funct_tension_crack	- MD code to simulate uniaxial tension boundary condition on PNC with an initial crack

------------------------------------------------------------------------------------------------------------------------------------------------------------------

For any queries write to abhirambr@iisc.ac.in

References

1. Abhiram B R and Debraj Ghosh, Atomic investigation on optimal interfacial bonding for enhanced fracture properties in polymer nanocomposites, Engineering Fracture Mechanics (2023): 109078
2. Abhiram B R and Debraj Ghosh, Influence of nanofiller agglomeration on fracture properties of polymer nanocomposite: Insights from atomistic simulation, Engineering Fracture Mechanics (2023): 109503


