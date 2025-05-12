# SNAP_IA_PROTOCOL
Those analyses follow a protocol named SNAP, which is in preparation. 

Citation: Vidal, J. P., ... & Barbeau, E. J. (in prep.) SNAP-IA: New standardized methodology for the assessment of the Interthalamic Adhesion using anatomical MRI.
![image](https://github.com/user-attachments/assets/efd2737d-d364-465e-80fd-dbe729bcd5e1)

# SNAP_IA_DALLAS
Interthalamic adhesion's masks on the Dallas Lifespan Brain Study. 

All associated T1w MRIs are publicly available: [https://openneuro.org/datasets/ds000030/versions/00016](https://openneuro.org/datasets/ds004856/versions/1.0.0)

The IA_overlap_wave1_DALLAS.zip file contains all the IA's masks by subject. Those masks are the overlap of two raters' segmentation when the Dice coefficient was superior to 0.80, demonstrating high agreement. 

Dallas_wave1_PVE_results.ods file is the FSL FAST segmentation output sheet overlapped with the IA's mask to estimate the partial volume effect (PVE, i.e mean rate of CSV). 

SNAP_IA_DALLAS_wave1.ods is the file with the IA's characterization, including its presence or absence, anatomical variant, and area corrected by the PVE. 
