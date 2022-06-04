# thesis
## Overview of the Repository
The #thesis repository contains data regarding time-series models with data taken from 5 ASEAN countries. The use of standard models (Delta-Normal, Historical Simulation, and the Boukdouh-Richardson-Whitelaw Hybrid Approach) and GARCH-type models (ARCH, GARCH, EGARCH, IGARCH, FIGARCH models) are used to estimate the value-at-risk (VaR) under the 5%, 1%, and 0.01% level of significance. Backtesting methods are also used to verify the models (VaR Violations, Kupiec Test, and Christoffersen Test) finally applying the Diebold-Mariano test to compare the models from one another.

## Folders in the Respository
1. data 
- A folder containing the .csv files used in the research found (folder: csv)
- A folder containing photos of the results (folder: photos)
- A summary of all the estimate VaR using the chosen models (folder: Summary1 and Summary2)
- A folder containng the Diebold-Mariano results using a 10-year time frame (folder: 2011-2021(10Y))
- A folder containng the Diebold-Mariano results using a 5-year time frame (folder: 2016-2021(5Y))

2. manuscipts
- The written manuscipt containing the results of the research
- The final presentation used in the the research

3. notebooks
- The folder contains the Jupyter notebooks used to obtain the results
- A folder containing the codes used to obtain the results of the Diebold-Mariano test (folder: diebold-mariano)
