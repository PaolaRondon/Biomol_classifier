# Title 📋

_Biomol_classifier <br/>

## Instructions 🛠️

_cns_smiles.txt | original txt with cns smiles and names <br/>
_non_cns_smiles.txt | original txt with  non cns smiles and names <br/>

_cns_molecues.csv | only cns molecules with all features <br/>
_non_cns_molecues.csv | only non ns molecules with all features <br/>

_molecules_v1.csv | all features <br/>
_molecules_v2csv | kbestfeatures after mutual_info_regression n times <br/>

_e_molecules.csv | experimental features <br/>

_f_classif_em_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features <br/>
_f_classif_emp_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features + possible features <br/>
_f_classif_best_k | best k features after f_classif cleaning. k=10,15,20,25 as testing values <br/>

_mic_non_zero_features | dataset after mutual_info_classif and weight zero features cleaning <br/>