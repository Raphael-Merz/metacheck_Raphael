# Find GitHub Links in Papers

GitHub links can be in PDFs in several ways.

## Usage

``` r
github_links(paper)
```

## Arguments

- paper:

  a paper object or paperlist object

## Value

a table with the GitHub url in the first (text) column

## Examples

``` r
github_links(psychsci)
#> # A tibble: 8 × 3
#>   href                                                          text_id paper_id
#>   <chr>                                                           <int> <chr>   
#> 1 https://github.com/addrummond/ibex                                 42 0956797…
#> 2 https://github.com/jmobrien/SpecCurve                             227 0956797…
#> 3 https://github.com/silveycat/vocab-syntax                         160 0956797…
#> 4 https://github.com/Spaak/context-congruency                       285 0956797…
#> 5 https://github.com/robloughnan/ABCD_Intelligence_Polygenic_S…      40 0956797…
#> 6 https://github.com/giacomobignardi/empirical-aesthetics-VCA/…     396 0956797…
#> 7 https://github.com/kobor-lab/Public-Scripts                        45 0956797…
#> 8 https://github.com/kobor-lab/Public-Scripts/blob/master/PedB…      82 0956797…
```
