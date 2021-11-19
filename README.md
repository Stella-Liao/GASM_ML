# Distance-Decay Parameter Calibration in Competing Destination Model by using Generalized Additive Model

## What have been done so far(11/19/21)
* Golden Selection for finding the optimal sigma value for the accessibility Aij
* Backfitting GAM to calibrate beta and delta values with respect to Dij and Aij

## Next Step
* Create the spatial smooth term `ss()` for `PoissonGAM()` in pyGAM package to intergrate the previous steps
* Apply our own competing destination model to explore the county-to-county migration flows

