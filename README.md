# Calculation-of-crystalline-particles
**Objective**--> We want to classify whether a molecule is part of the crystal lattice or not and then plot the number of crystalline molecules as a function of time. 

**Method**--> The algorithm for classifying a molecule is adapted from the work of Salvalaglio at al, DOI: https://doi.org/10.1021/ja307408x.
The degree of crystallinity, was measured as the product of two functions describing the local density, and local order, around a given molecule. 
Local density is calculated by summing the number of molecules within a radial distance, *r* around a given molecule and local orientation is dependent on the angle between two molecules along a bond vector, present within radius *r*.

**Features**--> MdAnalysis library is used to work with trajectory and topology files generated in gromacs. 
Matplotlib is used to develop plots of Number of crystalline molecules(Nc) as a function of time.

**Tests**--> Urea is worked out as an example (The proposed scheme can be tested on other molecular crystals.)
