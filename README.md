# SNAP_IA_DALLAS
Interthalamic adhesion's mask on the DALLAS dataset

# SNAP_IA_DALLAS
Interthalamic adhesion's masks on the Dallas Lifespan Brain Study. 

All associated T1w MRIs are publicly available: [https://openneuro.org/datasets/ds000030/versions/00016](https://openneuro.org/datasets/ds004856/versions/1.0.0)
Those analyses follow a protocol named SNAP, which is in preparation. 

The IA_overlap_wave1_DALLAS.zip file contains all the IA's masks by subject. Those masks are the overlap of two raters' segmentation when the Dice coefficient was superior to 0.80, demonstrating high agreement. 

Dallas_wave1_PVE_results.ods file is the FSL FAST segmentation output sheet overlapped with the IA's mask to estimate the partial volume effect (PVE, i.e mean rate of CSV). 

SNAP_IA_DALLAS_wave1.ods is the file with the IA's characterization, including its presence or absence, anatomical variant, and area corrected by the PVE. 
