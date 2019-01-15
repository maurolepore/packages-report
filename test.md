test.R
================
LeporeM
Tue Jan 15 18:02:22 2019

``` r
devtools::session_info()
```

    ## - Session info ----------------------------------------------------------
    ##  setting  value                       
    ##  version  R version 3.5.2 (2018-12-20)
    ##  os       Windows 10 x64              
    ##  system   x86_64, mingw32             
    ##  ui       RTerm                       
    ##  language (EN)                        
    ##  collate  English_United States.1252  
    ##  ctype    English_United States.1252  
    ##  tz       America/New_York            
    ##  date     2019-01-15                  
    ## 
    ## - Packages --------------------------------------------------------------
    ##  package     * version    date       lib source                           
    ##  assertthat    0.2.0      2017-04-11 [1] CRAN (R 3.5.0)                   
    ##  backports     1.1.3      2018-12-14 [1] CRAN (R 3.5.1)                   
    ##  callr         3.1.1      2018-12-21 [1] CRAN (R 3.5.1)                   
    ##  cli           1.0.1      2018-09-25 [1] CRAN (R 3.5.1)                   
    ##  crayon        1.3.4      2017-09-16 [1] CRAN (R 3.5.1)                   
    ##  desc          1.2.0      2018-12-17 [1] Github (r-lib/desc@42b9578)      
    ##  devtools      2.0.1      2018-10-26 [1] CRAN (R 3.5.1)                   
    ##  digest        0.6.18     2018-10-10 [1] CRAN (R 3.5.1)                   
    ##  evaluate      0.12       2018-10-09 [1] CRAN (R 3.5.1)                   
    ##  fs            1.2.6      2018-08-23 [1] CRAN (R 3.5.1)                   
    ##  glue          1.3.0      2018-07-17 [1] CRAN (R 3.5.1)                   
    ##  highr         0.7        2018-06-09 [1] CRAN (R 3.5.0)                   
    ##  htmltools     0.3.6      2017-04-28 [1] CRAN (R 3.5.0)                   
    ##  knitr         1.21       2018-12-10 [1] CRAN (R 3.5.1)                   
    ##  magrittr      1.5        2014-11-22 [1] CRAN (R 3.5.1)                   
    ##  memoise       1.1.0.9000 2018-12-13 [1] Github (hadley/memoise@1650ad7)  
    ##  pkgbuild      1.0.2      2018-10-16 [1] CRAN (R 3.5.1)                   
    ##  pkgload       1.0.2      2018-10-29 [1] CRAN (R 3.5.1)                   
    ##  prettyunits   1.0.2      2015-07-13 [1] CRAN (R 3.5.0)                   
    ##  processx      3.2.1      2018-12-05 [1] CRAN (R 3.5.1)                   
    ##  ps            1.3.0      2018-12-21 [1] CRAN (R 3.5.2)                   
    ##  R6            2.3.0      2018-10-04 [1] CRAN (R 3.5.1)                   
    ##  Rcpp          1.0.0      2018-11-07 [1] CRAN (R 3.5.1)                   
    ##  remotes       2.0.2      2018-10-30 [1] CRAN (R 3.5.2)                   
    ##  rlang         0.3.1      2019-01-08 [1] CRAN (R 3.5.2)                   
    ##  rmarkdown     1.11       2018-12-08 [1] CRAN (R 3.5.1)                   
    ##  rprojroot     1.3-2      2018-01-03 [1] CRAN (R 3.5.0)                   
    ##  sessioninfo   1.1.1      2018-11-05 [1] CRAN (R 3.5.1)                   
    ##  stringi       1.2.4      2018-10-21 [1] Github (gagolews/stringi@6c867b9)
    ##  stringr       1.3.1      2018-05-10 [1] CRAN (R 3.5.1)                   
    ##  testthat      2.0.1      2018-10-13 [1] CRAN (R 3.5.1)                   
    ##  usethis       1.4.0.9000 2019-01-09 [1] Github (r-lib/usethis@85bf30a)   
    ##  withr         2.1.2      2018-03-15 [1] CRAN (R 3.5.1)                   
    ##  xfun          0.4        2018-10-23 [1] CRAN (R 3.5.1)                   
    ##  yaml          2.2.0      2018-07-25 [1] CRAN (R 3.5.1)                   
    ## 
    ## [1] C:/Users/LeporeM/Documents/R/R-3.5.2/library
