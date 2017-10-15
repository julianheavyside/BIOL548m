Population demographics modelling using the `popbio` R package
================
Julian Heavyside
October 15, 2017

-   [Using the `popbio` package to work with some teasel data from Werner and Caswell](#using-the-popbio-package-to-work-with-some-teasel-data-from-werner-and-caswell)

### Using the `popbio` package to work with some teasel data from Werner and Caswell

The `teasel` dataset can be loaded from the `popbio` library. The data are simply the transition and fertility matrices from the teasel experiment

``` r
data("teasel")
knitr::kable(teasel)
```

|           |  seed1|  seed2|  small|  medium|  large|  flowering|
|-----------|------:|------:|------:|-------:|------:|----------:|
| seed1     |  0.000|   0.00|  0.000|   0.000|  0.000|    322.388|
| seed2     |  0.966|   0.00|  0.000|   0.000|  0.000|      0.000|
| small     |  0.013|   0.01|  0.125|   0.000|  0.000|      3.488|
| medium    |  0.007|   0.00|  0.125|   0.238|  0.000|     30.170|
| large     |  0.008|   0.00|  0.038|   0.245|  0.167|      0.862|
| flowering |  0.000|   0.00|  0.000|   0.023|  0.750|      0.000|
