# p-doped_silicon

---------------------------------------------------------------------------------

Written by Ankang Liu (email: liuankan@msu.edu) and Mahmoud Elewa (email:khalafel@msu.edu), Michigan State University, 2025.

---------------------------------------------------------------------------------

Here, we present the supplemental code for our paper "A Liu and M Dykman, [Effect of hole-strain coupling on the eigenmodes of semiconductor-based nanomechanical systems](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.111.235410)".

"p-type_semiconductor_elasticity_code.zip" archive contains three Mathematica notebook files in it:
(1) "two-band_model_Si.nb" shows analytically how the energy dispersion laws for the light- and heavy-hole bands are expanded in power series of strain tensor. Then, it uses Mathematica built-in function "NIntegrate" to calculate the hole-induced corrections to the elasticity parameters in p-type silicon up to the fourth order. The code here simply utilizes the analytical expressions derived in our preprint and the silicon parameters from Winkler's book to perform the calculations. The correction to any component of the elastic constant in the two-band approximation can be calculated for a given hole density and temperature using this file.

(2) "two-band_model_GaAs.nb" is the same as "two-band_model_Si.nb" but uses the GaAs parameters given in Winkler's book to calculate the hole-induced corrections to the elasticity parameters for p-type GaAs.

(3) "three-band_model_Si.nb" gives the code that we have used to numerically evaluate the hole-induced corrections to the elasticity parameters in p-type silicon when the spin split-off hole band is taken into account. Details of the numerical method used here can be found in our preprint as well as the comments in the file. In this notebook, only certain combinations of the second- and fourth-order elastic constants, which are relevant to the MEMS modes we have studied in our preprint, are calculated.

We also added the code for our cross-kerr analysis relevant for the paper "A. Liu, M. T. Elewa, and M. I. Dykman, Cross-Kerr mode coupling in p-doped semiconductor nanomechanical resonators".

"cross_kerr_code.zip" archive contains three Mathematica notebook files in it:
(1) "Analytical_expressions_for_cross_kerr_shifts.nb" shows analytically the calculations for the induced cross-Kerr frequency shift of the Lame mode due to the torsional mode and the torsional mode due to the Lame mode. 

(2) "three-band_model_create_cijkl_cross_kerr_n.nb" shows the calculation of the density dependence of the hole induced corrections to the elasticity parameters in p-type silicon for a given temperature. The same three band model that was used in the self-kerr was also used here.

(3) "three-band_model_create_cijkl_cross_kerr_T.nb" shows the calculations of the temperature dependence of the hole induced corrections to the elasticity parameters in p-type silicon for a given density. 

You may need to install Mathematica in order to open and run the files. Please feel free to play with the code –– you may use it to reproduce our reported results in the preprint or modify it accordingly for your own purposes. Should you have any questions, please do not hesitate to contact us.

---------------------------------------------------------------------------------
