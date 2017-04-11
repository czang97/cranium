An R package to quantify radial bridge images

Installation
------------

``` r
install.packages("devtools")
devtools::install_github("beanumber/cranium")
```

``` r
file <- "~/Data/barresi/AT_1_Probabilities.h5"
library(tidyverse)
tidy_brain <- file %>%
  read_h5() %>%
  tidy()
plot3d(tidy_brain)
```
