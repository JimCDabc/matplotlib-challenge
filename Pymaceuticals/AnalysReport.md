# Analysis Report for Pymaceuticals

Pymaceuticals Inc. Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. The data in this analysis reflect screenings for potential treatments to squamous cell carcinoma (SCC).  Data collected during these trials cover screenings for drug treatments: Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Propriva, Ramicane, Stelasyn, Zonifero, and a Placebo

The drug treatments in focus of this report include Capomulin, Infubinol, Ketapril, and a Placebo.


## Tumor Response to Treatment

The analysis of Tumor Response to Treatment compares the mean change in volume of tumors in the mice subjects over the duration of the trials.
For the 4 drug treatments in focus for the assignment (Capomulin, Infubinol, Ketapril, and the Placebo), 
* **Capomulin** appears to be effective at reducing tumor volume for SCC in mice.  
* All other drug treatments do not have noticible effect on reducing tumor volume

![Fig 1: Tumor Volume over Time](./Results/TumorVolume_vs_Time_4drugs.png)


## Metastatic Spread during Treatment
The analysis for Metastatic Spread during Treatment compares the mean of number of Metastatic sites occuring in mice subjects over the duration of the trials.  

For the 4 drug treatments in focus for the assignment (Capomulin, Infubinol, Ketapril, and the Placebo)
* **Capomulin** is most effective at lowering occurence of metastatic sites for SCC in mice.
* All other drug treatments do not have noticible effect on reducing tumor volume
* The standard error for Capomulin is well below that for Placebo and the other drug treatments.  So visually the lower metastatic rate for Capomulin seems statitically relevant.


![Fig 2: Metastatic Sites over Time](./Results/MetastaticSites_vs_Time_4drugs.png)

## Survival Rates
The analysis of Survival Rates compares the number of mice still alive for each drug treatment across the time points over the duration of the trials.  Counts are taken every 5 days.

For the 4 drug treatments in focus for the assignment (Capomulin, Infubinol, Ketapril, and the Placebo)
* **Capomulin** had the highest survival rate with an 84% survivor rate
* The placebo had a 44% survivor rate.  The other 2 treatments fared the same or worse.  (Infubril had a 36% survivor rate.  Ketapril had a 44% survivor rate.)


![Fig 3: Survival Rates](./Results/survivalRates_4drugs.png)


## Summary
The summary chart shows mean percentage tumor change over the 45 day trial period for each drug treatment.   Capomulin treatment resulted in a 19.48% reduction in tumor volume in the mouse subjects.   The placebo and the other 2 treatments had much worse results with ~50% increase in tumour volume in mouse subjects across the duration of the trial.


![Fig 4: Tumor Change over 45 day period](./Results/TumorChange_4drugs.png)


## Aditional Notes
Analysis of data from treaments not in focus here inidicate that Ramicane is also effective at reducing tumor volume, limiting metastatic sites, and improving survival rates of the mouse subjects


```python

```
