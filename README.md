# Distance-Decay Parameter Calibration in Competing Destination Model by using Generalized Additive Model

## What have been done so far(12/20/21)
* Golden Selection for finding the optimal sigma value for the accessibility Aij
* Backfitting GAM to calibrate beta and delta values with respect to Dij and Aij
* Data Cleaning for county-to-county migration data, which is showed in `data processing` notebook
* Migration data could be accessed and downloaded though this [link](https://docs.google.com/spreadsheets/d/1LPuym06RNvZtMeQzpGp2mprlbRQfFkAj/edit?usp=sharing&ouid=103306673501254470520&rtpof=true&sd=true)

## Next Step
* Improve the current codes for GAM algorithm with golden section search 
* Apply our own competing destination model to explore the county-to-county migration flows

