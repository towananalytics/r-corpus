## Resubmission / submission by new maintainer

This is a resubmission, by a new maintainer (Leslie Huang), by agreement with the previous maintainer (Patrick O. Perry).

## Release summary

version 0.10.1 fixes code that was breaking due to changes in r-devel (4.0.0), referenced here: https://stat.ethz.ch/pipermail/r-devel/2020-February/079049.html

## Test environments

- local OS X install, R 3.6.2
- linux, R oldrel / release / devel (travis-ci)
- windows server 2012, R 3.6.3 (appveyor)

## R CMD check results

No errors, warnings, or notes. 

## Reverse dependencies

- stylest
- GenEst
- crqanlp

The bug fix resolves an error that would have been propagated downstream to the reverse dependencies.