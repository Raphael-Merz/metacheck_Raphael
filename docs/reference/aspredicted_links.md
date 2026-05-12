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

a table with the AsPredicted url in the first (text) column

## Examples

``` r
aspredicted_links(psychsci)
#> # A tibble: 69 × 9
#>    text_id paragraph_id section_id text    page_number paper_id formatted header
#>      <int>        <int>      <int> <chr>         <int> <chr>    <chr>     <chr> 
#>  1      24            8          2 https:…          NA 0956797… NA        Short…
#>  2      30           11          4 https:…          NA 0956797… NA        Method
#>  3      31           10          3 https:…          NA 0956797… NA        Disti…
#>  4      33           12          4 https:…          NA 0956797… NA        Subje…
#>  5      36           10          2 https:…          NA 0956797… NA        Method
#>  6      40           12          2 https:…          NA 0956797… NA        State…
#>  7      40           12          2 https:…          NA 0956797… NA        State…
#>  8      40           12          2 https:…          NA 0956797… NA        State…
#>  9      40           12          2 https:…          NA 0956797… NA        State…
#> 10      42           12          3 https:…          NA 0956797… NA        Open …
#> # ℹ 59 more rows
#> # ℹ 1 more variable: section_type <chr>
```
