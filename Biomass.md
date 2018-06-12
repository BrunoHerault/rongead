BIOMASS nitidae
================
Bruno Hérault
12/06/2018

-   [Data Uploading](#data-uploading)
    -   [Including Plots](#including-plots)

Data Uploading
==============

``` r
library(knitr)
library(readxl)
```

    ## Warning: package 'readxl' was built under R version 3.4.4

``` r
data<-read_excel("data.xls")
kable(summary(data))
```

|     | Id\_Parcelle     | Codification Parcelles | Superficie en ha | Nom\_scientifique | wood density g/cm^3 |     DHP\_cm     |
|-----|:-----------------|:-----------------------|:-----------------|:------------------|:--------------------|:---------------:|
|     | Length:4771      | Length:4771            | Min. :0.200      | Length:4771       | Min. :0.2110        |   Min. : 7.006  |
|     | Class :character | Class :character       | 1st Qu.:1.000    | Class :character  | 1st Qu.:0.4090      | 1st Qu.: 23.000 |
|     | Mode :character  | Mode :character        | Median :1.500    | Mode :character   | Median :0.5230      | Median : 35.500 |
|     | NA               | NA                     | Mean :2.678      | NA                | Mean :0.5028        |  Mean : 42.478  |
|     | NA               | NA                     | 3rd Qu.:3.500    | NA                | 3rd Qu.:0.5800      | 3rd Qu.: 55.000 |
|     | NA               | NA                     | Max. :8.200      | NA                | Max. :0.9260        |  Max. :222.930  |

Including Plots
---------------

You can also embed plots, for example:

![](Biomass_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
