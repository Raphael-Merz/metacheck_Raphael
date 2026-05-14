# Find OSF Links in Papers

OSF links can be tricky to find in PDFs, since they can insert spaces in
odd places, and view-only links that contain a ? are often interpreted
as being split across sentences. This function is our best attempt at
catching and fixing them all.

## Usage

``` r
osf_links(paper)
```

## Arguments

- paper:

  a paper object or paperlist object

## Value

a table with the OSF url in the first (href) column

## Examples

``` r
osf_links(psychsci)
#> # A tibble: 451 × 4
#>    href                                               link_text text_id paper_id
#>    <chr>                                              <chr>       <int> <chr>   
#>  1 https://osf.io/e2aks/                              NA            206 0956797…
#>  2 https://osf.io/tvyxz/wiki/view/                    NA            209 0956797…
#>  3 https://osf.io/tvyxz/wiki/view/                    NA            253 0956797…
#>  4 https://osf.io/t9j8e/?view_only=f171281f212f44359… NA             NA 0956797…
#>  5 https://osf.io/tvyxz/wiki/1.%20View%20the%20Badge… NA             NA 0956797…
#>  6 https://osf.io/eky4s/                              NA             73 0956797…
#>  7 https://osf.io/tvyxz/wiki/1.%20View%20the%20Badge… NA             NA 0956797…
#>  8 https://osf.io/tvyxz/wiki/1.%20View%20the%20Badge… NA             NA 0956797…
#>  9 https://osf.io/xgwhk                               NA            243 0956797…
#> 10 https://osf.io/tvyxz/wiki/1.%20View%20the%20Badge… NA             NA 0956797…
#> # ℹ 441 more rows
```
