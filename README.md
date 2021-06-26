# Surfs_up

## Overview 

The purpose of this analysis was to retrieve temperature information in Oahu for the months of June and December, and contrast the differences to determine whether an ice cream shop can be opened for business year-round. The analysis code can be found here: [SurfsUp_Challenge_Code](https://github.com/fadlnabbouh/surfs_up/blob/main/SurfsUp_Challenge.ipynb).

## Results 

The results of the analysis for June and December can be seen in the following images: 
June: 
![june_statistics](https://github.com/fadlnabbouh/surfs_up/blob/main/Resources/june_statistics.png)
December: 
![december_statistics](https://github.com/fadlnabbouh/surfs_up/blob/main/Resources/december_statistics.png)

Three key differences between June and December are: 
- The average temperature in June is higher than December. June has an average temperature of 74.9 degrees farenheit, and a median of 75 degrees. December's mean temperature is around 71.0 degrees farenheit, with a median of 71 degrees. June is approximately 4 degrees warmer than December, although this difference is not significantly large.
- The range of temperatures in June is 85-64 or 21 degrees while in December its 83-56 or 27 degrees. This shows that the temperature in December fluctuates more than it does June. This result can also be seen in the standard deviation, where the STD is 3.75 in December but only 3.26 in June, showing more fluctuation in December. The ranges, however, do not differ significantly, meaning the temperature is relatively consistent year round.
- The number of observations differ slightly between June and December. June has 1700 observations while December has 1517. Some dates in December are missing. However, having over 1500 data point in both months is great and should not be a cause for alarm. My analysis should still be valid.

## Summary 

After analyzing the June data relative to the December data, I can see that the temperature on Oahu is consistent. June has an average temperature of around 75 Degrees, while December is around 71 Degrees. The range in temperatures is greater in December, but not significantly greater. This means that Oahu's weather is relatively consistent year round and would be a great location for an ice cream shop. 

To further my analysis, I can conduct a few more queries: 
- I would conduct queries into precipitation patterns to determine how consistent precipitation (or lack of) is in Oahu. Analyzing the precipitation patterns will allow me to determine whether an ice cream shop is a reasonable business in Oahu or whether it is likely to be rained out. 
- Another query I would consider is querying weather information from each available station in Oahu. Weather station queries combined with the weather analysis may indicate a more optimal location for the ice cream shop. 