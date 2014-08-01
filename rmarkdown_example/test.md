# Trying Rmarkdown
Ben Best  
August 1, 2014  

## Introduction {-}

The Ocean Health Index [@halpern_index_2012; @selig_assessing_2013] derives most of its pressures from Halpern et al. [-@halpern_global_2008].

## Food Provision: Fisheries

Amount of sustainable wild-caught seafood compared to the max sustainable

$$
x_{FIS} =  (\prod_{g=1}^{6} SS_{i,g}^{C_{i,g}})^\frac{1}{\sum{C_{i,g}}}
$$

Variables:

- $SS$: stock status score, based on B/Bmsy and an underharvest penalty adjustment
- $C$: total catch
- $i$: OHI reporting region
- $g$: level of taxonomic grouping (ISSCAAP)</small>


## Default Rmarkdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```

You can also embed plots, for example:

![Scatterplot of cars.](./test_files/figure-html/unnamed-chunk-2.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## References {-}
<!-- placeholder for References in toc --!>
