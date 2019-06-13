# Entitlement data analysis

This repository contains the critical data and scripts to replicate the analysis in Trott & Rossano (Submitted).

# Details on the data

## Experiment 1

Found in `exp1_critical.csv`.

The main variables of interest are:  
* `condition`: high vs. low entitlement.  
* `request`: raw response produced by participant.  
* `formatting`: annotated formatting (M, EM, D, IS).  
* `reason_final`: final annotation for whether a reason was given.  
* `Just2.ST`: annotation for whether repayment was offered.  

Additionally, the humnan-normed estimates:  
* `mean_entitlement`  
* `mean_power`  
* `mean_imposition`  
* `mean_distance`  

With random effects:  
* `subject` (participant)  
* `stimNum` (item)  