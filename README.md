# MatPlotLib-Challenge
Module 5 Assignment

This notebook takes data from the Mouse_metadata and Study_results excel workbooks, cleaning and displaying the data in various graphs.
Mice were given a drug and their tumor size was monitored to see the effects of that drug on the tumor.

Observation 1: Capomulin and Ramicane had approximately 50 more mice that were monitored compared to the other drugs. This increased sample size would have likely provided more accuracy with the results
                Having a smaller population size would mean that our inferences from the data may not be entirely accurate.
                The difference between the two larger populations and the rest of the populations is approximately 25%. 

Observation 2: Looking at the IQRs for Capomulin, Ramicane, Infubinol, and Ceftamin, we can see that Capomulin and Ramicane both had consistently lower tumor sizes than the other two.
                Infubinol has a single data point that is similar to the results of Capomulin and Ramicane, but it is outside of its IQR and should be considered an outlier.
                Capomulin's mean (tumor volume) is slightly biased towards the upper IQR while Ramicane's mean sits more in the middle.

Observation 3: The r-value for the linear regression plot is 0.708, meaning there is a strong correlation between weight and average tumor volume.
                Generally, it appears that mouse size is proportional to the tumor's volume (i.e. tumor volume increases as mouse size increases).
                However, mice that weighed in a 17 grams saw the widest range or tumor volumes especially the two points that appear to be further from the regression line than the other points.