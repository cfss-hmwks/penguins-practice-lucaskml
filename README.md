## R Markdown

Here we are going to learn a bit about penguins!

## Penguins

See below for averages on penguins.

    ## Warning: package 'dplyr' was built under R version 4.3.3

    ## Warning: package 'palmerpenguins' was built under R version 4.3.3

    ## # A tibble: 3 × 3
    ##   sex    avg_bill avg_mass
    ##   <fct>     <dbl>    <dbl>
    ## 1 female     37.3    3369.
    ## 2 male       40.4    4043.
    ## 3 <NA>       37.8    3540

## Your work

Summarize the dataset in a meaningful way (use AT LEAST two of the key
functions from slide \#12)

    penguins_bill_length = arrange(penguins, bill_length_mm)
    penguins_renamed = arrange(penguins, body_mass_g = 'body_mass')

    penguins_renamed

    ## # A tibble: 344 × 8
    ##    species island    bill_length_mm bill_depth_mm flipper_length_mm body_mass_g
    ##    <fct>   <fct>              <dbl>         <dbl>             <int>       <int>
    ##  1 Adelie  Torgersen           39.1          18.7               181        3750
    ##  2 Adelie  Torgersen           39.5          17.4               186        3800
    ##  3 Adelie  Torgersen           40.3          18                 195        3250
    ##  4 Adelie  Torgersen           NA            NA                  NA          NA
    ##  5 Adelie  Torgersen           36.7          19.3               193        3450
    ##  6 Adelie  Torgersen           39.3          20.6               190        3650
    ##  7 Adelie  Torgersen           38.9          17.8               181        3625
    ##  8 Adelie  Torgersen           39.2          19.6               195        4675
    ##  9 Adelie  Torgersen           34.1          18.1               193        3475
    ## 10 Adelie  Torgersen           42            20.2               190        4250
    ## # ℹ 334 more rows
    ## # ℹ 2 more variables: sex <fct>, year <int>

# Final task

You need to make a README.md doc – practice by outputting a .md file
here and renaming it to README.md before pushing to github
