# Title 📋

Biomol_classifier <br/>

## Instructions 🛠️

cns_smiles.txt | original txt with cns smiles and names <br/>
non_cns_smiles.txt | original txt with  non cns smiles and names <br/>

cns_molecues.csv | only cns molecules with all features <br/>
non_cns_molecues.csv | only non ns molecules with all features <br/>

molecules.csv | all features <br/>
e_molecules.csv | experimental features <br/>

f_classif_em_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features <br/>
f_classif_emp_molecules.csv | kbestfeatures after f_classif and data cleaning. Experimental features + must have features + possible features <br/>
f_classif_best.csv | best k features after f_classif cleaning. k=1 to k=all-1 as values <br/>

mic_best.cvs | best k features after mutual info classif cleaning. k=1 to k=all-1 as values<br/>


best_df_KKN | best data frame after forward selection. mic, normal and f_classif were included in the forward feature selection<br/>
best_df_linear | best data frame after forward selection. mic, normal and f_classif were included in the forward feature selection<br/>