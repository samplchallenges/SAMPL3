Thank you for downloading data for SAMPL3.  In the data packet you may find several varieties of files:

	.txt files contain an overview of the challenge as well as background information.

	.ism files contain isomeric SMILES strings for each of the molecules in the data set.

	.sdf files contain modeled 3D coordinates for each molecule in SD format.  See disclaimer below.

	.data files are example plain text files for submission of your data.  Please read the information at the head of the file which describes the required format for data submission.  Ideally, you should modify the provided file and turn it in when you submit predictions.

**DISCLAIMER** :  The 3D coordinates of molecules are generally included only to provide an example 3D structure for those who prefer not to use SMILES, and these structures are not intended to be a particularly meaningful conformation.  Determining appropriate conformation, protonation state, and tautomer state are considered to be part of the SAMPL challenge.

The deadline for submission of predictions is June 20, 2011.  A complete submission will include the data file referenced above, as well as another plaintext file with a detailed description of the prediction method.

Thank you for taking part in SAMPL, and we hope this experience will spark insight and spur discussions regarding these predictions and the general state of our field.  We hope you can join us for the SAMPL workshop, which will take place at Stanford at the beginning of August 2011.  

********************************************************************
Host-Guest Binding Affinity Prediction Challenge
********************************************************************

********************
**  Host1 System  **
********************

A key paper relating to this host with a different set of guests can be found in the following reference:
Ma et al. Acyclic cucurbit[n]uril congeners are high affinity hosts. J. Org. Chem. (2010) vol. 75 (14) pp. 4786-95
http://pubs.acs.org/doi/abs/10.1021/jo100760g

The guest molecules are provided as .sdf files, as described previously.  Please be aware of the disclaimer above about the 3D structures.  Also note that the affinity of the h1.guest1 molecule was measured using a racemic mixture.  Both stereoisomers are provided in the .sdf file.  Please submit your prediction for the racemic mixture, as well as for each stereoisomer if possible.

There are two files provided which contain the host molecule.  The PDB file includes a lower-occupancy conformation of one end of the molecule as an alternate location, while the SDF file only contains the higher occupancy conformer.  The host structure is derived from the x-ray coordinates provided in the supplemental information of the paper referenced above.

The binding affinities of the guests molecules for host1 were determined using a 20 mM sodium phosphate buffer at pH 7.4 in one or more of the following ways:
a) Direct 1H NMR titration of a fixed concentration of guest with an increasing concentration of host
b) Direct UV/Vis titration of a fixed concentration of dye molecule with an increasing concentration of host
C) Direct fluorescence titration of a fixed concentration of dye molecule with an increasing concentration 
D) Competition assay involving the titration of guest into a fixed concentration of dye and host and observing the change in spectroscopic parameter (e.g. NMR chemical shift, UV/Vis absorbance, or Fluorescence intensity.

*****************************
**  Host2 and Host3 System **
*****************************

The host and guest molecules are provided as .sdf files, as described previously.  Please be aware of the disclaimer above about the 3D structures.  Host 3D structures were obtained from the CSD.  

The binding affinities of the guests molecules for host2 and host3 were determined using isothermal titration calorimetry at 300 K in 10 mM sodium phosphate buffer, pH 7.0.

