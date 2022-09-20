Data import
================

``` r
library(tidyverse)
```

    ## -- Attaching packages --------------------------------------- tidyverse 1.3.2 --
    ## v ggplot2 3.3.6      v purrr   0.3.4 
    ## v tibble  3.1.8      v dplyr   1.0.10
    ## v tidyr   1.2.0      v stringr 1.4.1 
    ## v readr   2.1.2      v forcats 0.5.2 
    ## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

## Read in some data

Read in thelitters dataset

``` r
litters_df = read.csv("./data/FAS_litters.csv")
```
