Parameters files for all runs used in the study: 
Formation of continental microplates through rift linkage: Numerical modelling and its application to the Flemish Cap and Sao Paulo Plateau.
Derek Neuharth, Sascha Brune, Anne Glerum, Christian Heine, J. Kim Welford
G-Cubed 2021


Model runs in the study used dealii 9.1.1.
The aspect version which includes additional plugins written by Anne Glerum can be found at: 
https://github.com/Djneu/microplate_study


Parameters are named by: Xoffset_Yoffset_crustalratio
e.g., 100x_200y_2510 is a model with a 100 km X offset, 200 km Y offset, and crustal ratio of 25:10

Files are divided in folders by regime diagram:

1. Reference models
	- Four parameter files for the runs with a Y offset of 300 km, crustal ratio of 25:10, and X offset of 100-400 km
   
2. Regime offset
	- 12 files with a crustal ratio of 25:10, and are X/Y offsets between 100 and 400 km.

4. Regime strength
	- 16 files with a Y offset of 300 km, X offset varied between 100 and 400 km, and crustal ratio between 35:0 to 10:25

3. Lithosphere thickness
	- 20 files with a Y offset of 300 km, crustal ratio of 25:10, X offset varied between 100 and 400 km,
          and lithsohpere thickness between 80 and 160 km. Naming convention is changed to Xoffset_Yoffset_lithospherethickness.prm