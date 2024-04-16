Global Disease Burden Analysis
================
REPLACE WITH THE AUTHOR NAMES
2024-04-16

# Introduction

This document synthesizes our analysis of the global disease burden for
selected countries, comparing the burden due to communicable, maternal,
neonatal, and nutritional diseases (CMNN), non-communicable diseases
(NCDs), and overall disease burden. We present tables and plots to
visualize the trends in disease burden over time and provide a summary
of our findings.

# Communicable, Maternal, Neonatal, and Nutritional Disease Burden

``` r
# Load necessary packages
pacman::p_load(tidyverse, knitr, here)

# Import the communicable diseases data
data_cmnn <- read_csv(here("data", "burden-of-disease-cmnn.csv"))
```

    ## Rows: 8100 Columns: 4
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (2): Entity, Code
    ## dbl (2): Year, DALYs (Disability-Adjusted Life Years) - Communicable, matern...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

## Table of Recent Estimates (2018 and 2019)

``` r
# Here render a table for the year 2018 and 2019 DALY burden for the three countries 
# Use kable() from the knitr package.
```

## Plot Showing Trends Over Time

``` r
# Here, plot a line graph showing the trend of DALY burden for the chosen countries over time. You can use ggplot2 to create this plot. Each country's line should be a different color.
```

## Summary

``` r
# Provide a brief analysis based on the data presented in the table and chart. Highlight any significant findings or patterns. About 3 sentences
```

# Non-Communicable Disease Burden

``` r
# Load necessary packages
pacman::p_load(tidyverse, knitr, here)

# Import the non-communicable diseases data
data_ncd <- read_csv(here("data", "burden-of-disease-ncd.csv"))
```

    ## Rows: 8010 Columns: 4
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (2): Entity, Code
    ## dbl (2): Year, DALYs (Disability-Adjusted Life Years) - Non-communicable dis...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

## Table of Recent Estimates (2018 and 2019)

``` r
# Here render a table for the year 2018 and 2019 DALY burden for the three countries 
# Use kable() from the knitr package.
```

## Plot Showing Trends Over Time

``` r
# Here, plot a line graph showing the trend of DALY burden for the chosen countries over time. You can use ggplot2 to create this plot. Each country's line should be a different color.
```

## Summary

``` r
# Provide a brief analysis based on the data presented in the table and chart. Highlight any significant findings or patterns. About 3 sentences
```

# Overall Disease Burden

``` r
# Load necessary packages
pacman::p_load(tidyverse, knitr, here)

# Import the overall disease data
data_overall <- read_csv(here("data", "burden-of-disease-all-causes.csv"))
```

    ## Rows: 8100 Columns: 4
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (2): Entity, Code
    ## dbl (2): Year, DALYs (Disability-Adjusted Life Years) - All causes - Sex: Bo...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

## Table of Recent Estimates (2018 and 2019)

``` r
# Here render a table for the year 2018 and 2019 DALY burden for the three countries 
# Use kable() from the knitr package.
```

## Plot Showing Trends Over Time

``` r
# Here, plot a line graph showing the trend of DALY burden for the chosen countries over time. You can use ggplot2 to create this plot. Each country's line should be a different color.
```

## Summary

``` r
# Provide a brief analysis based on the data presented in the table and chart. Highlight any significant findings or patterns. About 3 sentences
```
