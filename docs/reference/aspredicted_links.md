# Find AsPredicted Links in Papers

Find AsPredicted Links in Papers

## Usage

``` r
aspredicted_links(paper)
```

## Arguments

- paper:

  a paper object or paperlist object

## Value

a table with the AsPredicted url in the first (href) column

## Examples

``` r
aspredicted_links(psychsci)
#> # A tibble: 68 × 4
#>    href                              link_text text_id paper_id        
#>    <chr>                             <chr>       <int> <chr>           
#>  1 https://aspredicted.org/ve2qn.pdf NA             24 0956797619876260
#>  2 https://aspredicted.org/ve2qn.pdf NA             33 0956797619876260
#>  3 https://aspredicted.org/ve2qn.pdf NA             95 0956797619876260
#>  4 https://aspredicted.org/mq97g.pdf NA            107 0956797620927967
#>  5 https://aspredicted.org/4gf64.pdf NA             31 0956797620948821
#>  6 https://aspredicted.org/8a6ta.pdf NA             58 0956797620948821
#>  7 https://aspredicted.org/rz98j.pdf NA            144 0956797620948821
#>  8 https://aspredicted.org/4gf64.pdf NA            179 0956797620948821
#>  9 https://aspredicted.org/8a6ta.pdf NA            179 0956797620948821
#> 10 https://aspredicted.org/vp4rg.pdf NA            179 0956797620948821
#> # ℹ 58 more rows
```
