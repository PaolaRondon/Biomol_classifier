# Title 📋

Biomol_classifier <br/>

## Instructions 🛠️

the optimized algorithm is inside the forward__feature_selection folder, same for results and other data <br/>

cns_smiles.txt | original txt with cns smiles and names <br/>
non_cns_smiles.txt | original txt with  non cns smiles and names <br/>

cns_smiles.txt and non_cns_smiles.txt were taken from: hose, A. K., Herbertz, T., Hudkins, R. L., Dorsey, B. D., & Mallamo, J. P. Knowledge-based, central nervous system (CNS) lead selection and lead optimization for CNS drug discovery. ACS Chemical Neuroscience, 3(1), pp 50–68, 2012.

cns_molecues.csv | only cns molecules with all features <br/>
non_cns_molecues.csv | only non ns molecules with all features <br/>

molecules.csv | all features <br/>
e_molecules.csv | experimental features <br/>

f_classif_em_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features <br/>
f_classif_emp_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features + possible features <br/>
f_classif_best.csv | best k features after f_classif cleaning. k=1 to k=all-1 as values <br/>

mic_best.cvs | best k features after mutual info classif cleaning. k=1 to k=all-1 as values<br/>

