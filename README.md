# Speciation_Collapse_Matlab_Code
The file contains a zipped file of matlab codes for the manuscript: Biodiversity loss through speciation collapse: mechanisms, warning signals, and possible rescue. 

The main matlab script is named as FST_Parallel_Entry. This script has three sections: Speciation, Disturbance and Environmental restoration. Each section can run independently when the othe two are commented. 

The section of Speciation aims for the emergence of incipient species pairs from a population with homozygous individuals. Repeat this program, and you can get a certian number of incipient species pairs. The random seed is set according to your local time. The information on incipient species is saved in dataFST which is a structure. The evoling history is saved in a couple of txt file: Pu.txt saves the ecological alleles of all individuals at each time. Pv.txt saves the mating alleles of all individuals at each time. Generation.txt saves the elapsing time for each mutation.    

The section of Disturbance demonstrates what happens when a certian level of disturbances is imposed to the incipient species pairs. There are two types of environmnetal disturbances: deteriorate visual conditions (update param.a1, param.a2, and pram.sigmav), and environmental homogenization (update param.u1).  To run this section, you definitely should have an incipient species pair. 

The last section demonstrates what happens if environment is restored. 


