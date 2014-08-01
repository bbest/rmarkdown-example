Introduction
------------

The Ocean Health Index (Halpern et al., 2012; Selig et al., 2013) derives most of its pressures from Halpern et al. (2008).

Food Provision: Fisheries
-------------------------

Amount of sustainable wild-caught seafood compared to the max sustainable

\[
x_{FIS} =  (\prod_{g=1}^{6} SS_{i,g}^{C_{i,g}})^\frac{1}{\sum{C_{i,g}}}
\]

Variables:

-   \(SS\): stock status score, based on B/Bmsy and an underharvest penalty adjustment
-   \(C\): total catch
-   \(i\): OHI reporting region
-   \(g\): level of taxonomic grouping (ISSCAAP)</small>

Default Rmarkdown
-----------------

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` {.r}
summary(cars)
```

    ##      speed           dist    
    ##  Min.   : 4.0   Min.   :  2  
    ##  1st Qu.:12.0   1st Qu.: 26  
    ##  Median :15.0   Median : 36  
    ##  Mean   :15.4   Mean   : 43  
    ##  3rd Qu.:19.0   3rd Qu.: 56  
    ##  Max.   :25.0   Max.   :120

You can also embed plots, for example:

![Scatterplot of cars.](./test_files/figure-markdown_github/unnamed-chunk-2.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

Github Markdown
---------------

To get github friendly Markdown document for cleanly tracking changes to document in Github, put the following output first:

    output:
      md_document:
        variant: "markdown_github"

NOTE: You need to run this **LAST** though, since knitting other formats wipes out the `test_files` directory. To return to the Knit button having other options (HTML, PDF, Word), move this output type below the first option.

References
----------

<!-- placeholder for References in toc -->


Halpern, B. S., Longo, C., Hardy, D., McLeod, K. L., Samhouri, J. F., Katona, S. K., … Zeller, D. (2012). An index to assess the health and benefits of the global ocean. *Nature*. doi:[10.1038/nature11397](http://dx.doi.org/10.1038/nature11397)

Halpern, B. S., Walbridge, S., Selkoe, K. A., Kappel, C. V., Micheli, F., D’Agrosa, C., … Watson, R. (2008). A Global Map of Human Impact on Marine Ecosystems. *Science*, *319*(5865), 948–952. doi:[10.1126/science.1149345](http://dx.doi.org/10.1126/science.1149345)

Selig, E. R., Longo, C., Halpern, B. S., Best, B. D., Hardy, D., Elfes, C. T., … Katona, S. K. (2013). Assessing Global Marine Biodiversity Status within a Coupled Socio-Ecological Perspective. *PLoS ONE*, *8*(4), e60284. doi:[10.1371/journal.pone.0060284](http://dx.doi.org/10.1371/journal.pone.0060284)
