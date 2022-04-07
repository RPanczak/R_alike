---
editor_options: 
  chunk_output_type: console
---

# Dataset overview 

Describing the data frame.  

## Example data

Using `mtcars`.  


```r
data(mtcars)
```

## Base


```r
str(mtcars)
```

```
## 'data.frame':	32 obs. of  11 variables:
##  $ mpg : num  21 21 22.8 21.4 18.7 18.1 14.3 24.4 22.8 19.2 ...
##  $ cyl : num  6 6 4 6 8 6 8 4 4 6 ...
##  $ disp: num  160 160 108 258 360 ...
##  $ hp  : num  110 110 93 110 175 105 245 62 95 123 ...
##  $ drat: num  3.9 3.9 3.85 3.08 3.15 2.76 3.21 3.69 3.92 3.92 ...
##  $ wt  : num  2.62 2.88 2.32 3.21 3.44 ...
##  $ qsec: num  16.5 17 18.6 19.4 17 ...
##  $ vs  : num  0 0 1 1 0 1 0 1 1 1 ...
##  $ am  : num  1 1 1 0 0 0 0 0 0 0 ...
##  $ gear: num  4 4 4 3 3 3 3 4 4 4 ...
##  $ carb: num  4 4 1 1 2 1 4 2 2 4 ...
```


## `report` package


```r
library(report)

report(mtcars)
```

```
## Warning: Following variable(s) were not found: n_Obs
```

```
## The data contains 32 observations of the following 11 variables:
## 
##   - mpg: n = 32, Mean = 20.09, SD = 6.03, Median = 19.20, MAD = 5.41, range: [10.40, 33.90], Skewness = 0.67, Kurtosis = -0.02, 0 missing
##   - cyl: n = 32, Mean = 6.19, SD = 1.79, Median = 6.00, MAD = 2.97, range: [4, 8], Skewness = -0.19, Kurtosis = -1.76, 0 missing
##   - disp: n = 32, Mean = 230.72, SD = 123.94, Median = 196.30, MAD = 140.48, range: [71.10, 472], Skewness = 0.42, Kurtosis = -1.07, 0 missing
##   - hp: n = 32, Mean = 146.69, SD = 68.56, Median = 123.00, MAD = 77.10, range: [52, 335], Skewness = 0.80, Kurtosis = 0.28, 0 missing
##   - drat: n = 32, Mean = 3.60, SD = 0.53, Median = 3.70, MAD = 0.70, range: [2.76, 4.93], Skewness = 0.29, Kurtosis = -0.45, 0 missing
##   - wt: n = 32, Mean = 3.22, SD = 0.98, Median = 3.33, MAD = 0.77, range: [1.51, 5.42], Skewness = 0.47, Kurtosis = 0.42, 0 missing
##   - qsec: n = 32, Mean = 17.85, SD = 1.79, Median = 17.71, MAD = 1.42, range: [14.50, 22.90], Skewness = 0.41, Kurtosis = 0.86, 0 missing
##   - vs: n = 32, Mean = 0.44, SD = 0.50, Median = 0.00, MAD = 0.00, range: [0, 1], Skewness = 0.26, Kurtosis = -2.06, 0 missing
##   - am: n = 32, Mean = 0.41, SD = 0.50, Median = 0.00, MAD = 0.00, range: [0, 1], Skewness = 0.40, Kurtosis = -1.97, 0 missing
##   - gear: n = 32, Mean = 3.69, SD = 0.74, Median = 4.00, MAD = 1.48, range: [3, 5], Skewness = 0.58, Kurtosis = -0.90, 0 missing
##   - carb: n = 32, Mean = 2.81, SD = 1.62, Median = 2.00, MAD = 1.48, range: [1, 8], Skewness = 1.16, Kurtosis = 2.02, 0 missing
```


## 
