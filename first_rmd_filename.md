First\_Rmarkdown
================
tom
2018-01-10

This is my RMD file.
--------------------

### I am exhausted.

### I have 3 courses to take today.

``` r
head(iris)
```

    ##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
    ## 1          5.1         3.5          1.4         0.2  setosa
    ## 2          4.9         3.0          1.4         0.2  setosa
    ## 3          4.7         3.2          1.3         0.2  setosa
    ## 4          4.6         3.1          1.5         0.2  setosa
    ## 5          5.0         3.6          1.4         0.2  setosa
    ## 6          5.4         3.9          1.7         0.4  setosa

first 6 rows of iris dataset.

This is an image of an Kim Jung En

![This is an image of an Kim Jung En](http://www.motorgraph.com/news/photo/201512/8167_35944_443.jpg)

let's go for the ggplot

``` r
install.packages("tidyr",repos = "http://cran.us.r-project.org")
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/l7/y2ztr08x2qb06_dtl31rdcz00000gn/T//Rtmp0NROI3/downloaded_packages

``` r
library(tidyverse)
```

    ## Loading tidyverse: ggplot2
    ## Loading tidyverse: tibble
    ## Loading tidyverse: tidyr
    ## Loading tidyverse: readr
    ## Loading tidyverse: purrr
    ## Loading tidyverse: dplyr

    ## Warning: package 'tidyr' was built under R version 3.4.2

    ## Warning: package 'dplyr' was built under R version 3.4.2

    ## Conflicts with tidy packages ----------------------------------------------

    ## filter(): dplyr, stats
    ## lag():    dplyr, stats

``` r
ggplot(data = mpg) + 
  geom_point(mapping = aes(x = displ, y = hwy, color = class))
```

![](first_rmd_filename_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-3-1.png)
