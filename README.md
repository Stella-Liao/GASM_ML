# Distance-Decay Parameter Calibration in Competing Destination Model(CDM) by using Generalized Additive Model (GAM)

## What have been done so far(2/4/22)
* `SpatialSmooth()` and`SpatialGAM()` is created (See in the 'Some Issues' notbook)
  * Considering the situation where not each origin will also be a destination
  * Providing another method to calculate the accessibility `Aij` in CDM
  * `SpatialGAM()` runs much faster than `CompeteDestination3()` while solving the issues mentioned in the 'Some Issues' notebook
  * An example of `SpatialGAM():`
       `SpatialGAM(y, 4, 5, austria, 1, austria_shp, is_Spatial = True, verbose = False)`    
* Data Cleaning for county-to-county migration data, which is showed in 'data processing' notebook
* Migration data could be accessed and downloaded though this [link](https://docs.google.com/spreadsheets/d/1LPuym06RNvZtMeQzpGp2mprlbRQfFkAj/edit?usp=sharing&ouid=103306673501254470520&rtpof=true&sd=true)

## Next Step
* Create `SpatialGAM` class and `SpatialSmooth` class instead of the methods we created so far
* Integrate the codes in SpInt module?

