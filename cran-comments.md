## Release summary

version 0.10.2 adds `rmarkdown` to `SUGGESTS` per https://github.com/yihui/knitr/issues/1864

## Test environments

- local OS X install, R 3.6.2
- linux, R oldrel / release / devel (travis-ci)
- windows server 2012, R 3.6.3 (appveyor)

## R CMD check results

No errors or warnings. 1 note regarding change in maintainer.

## Reverse dependencies

- stylest
- GenEst
- crqanlp

The bug fix resolves an error that would have been propagated downstream to the reverse dependencies.
