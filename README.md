# Mol2Vec
Unsupervised Learning Applied to Polycyclic Aromatic Hydrocarbon Spectral Databases for Astrochemistry  

The raw NASA AMES data is at :  

- Experimental - pahdb-complete-experimental-v3.00_SDfqt0.ascii  
- Theoretical - pahdb-complete-theoretical-v3.20_TsTF3p.ascii  

After processing, SMILES format of molecules can be found at :  

- Experimental -  

  - ExperimentalSMI.smi  
  
- Theoretical -  
  
  - TheoreticalSMI.smi (All molecules)  
  - TheoreticalSMI_Pruned.smi (Only molecules that could be processed)  
  
All pkl files have preprocessed data  

Data table - "Theoretical Database.csv"
  
Preprocessing code file - Morgan Fingerprinting.ipynb  
  
Main data analysis file - Mol2Vec - Final.ipynb  
