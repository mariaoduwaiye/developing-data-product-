DEV DATA PRODUCT
========================================================
author: MARIA ODUWAIYE
date: 06/02/2019
autosize: true

First Slide
========================================================

For more details on authoring R presentations please visit 
Description of the shiny app and the presenation
In the enclosed Shiny app, I use the mtcars dataset. I use a slide bar that changes the number of cylinders. The miles per gallon (MPG) of cars with this specific number of cylinders is plotted as a function of their weights.

For each cylinder, a linear regression model is implemented and plotted on top of the data. Also, the linear fit equation is printed on the plot for each number of cylinders.

Slide With Code
========================================================
Here is a summary of the mtcars dataset.

```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================
Strength of dependence of MPG on Weigth for different number of cylinders
Clearly, the dependence of MPG on car weight is strongest for 4-cylinder cars. The 6- and 8-cylinder cars have somewhat similar dependence of MPG on their weight.
![plot of chunk unnamed-chunk-2](DEV DATA PRODUCT-figure/unnamed-chunk-2-1.png)
