
# indexthis 2.1.0

## comply to new CRAN rules

- replace R's non-API STRING_PTR with STRING_PTR_RO

# indexthis 2.0.0

## New features

- new function `indexthis_vendor` to automatically populate a package directory with the `to_index` function. Requires no user intervention (except in one case).

## Other

- remove `Rcpp` dependency

- remove checking functions to facilitate vendoring

# indexthis 1.0.1

- fix bug when a numeric vector considered as int contained NA values in a specific branch of the algorithm
- fix bug: prevent R objects (converted to character within C) to be garbage collected
- add compatibility with R < 4.1.0

# indexthis 1.0.0

## information

- initial version: only contains the function `to_index`.
