# rrtools
Draft repo for project reproducibility tools


## rr testing framework

-  Test _objects_, not functions
-  Have all objects produced by analyses and Rmds available to the testing scripts
-  Produce testing reports, including visuals, not just boolean responses

## rrtools package functions

-  `use_docker()` - Generate an appropriate dockerfile.  Most likely an image based on the current R version.
-  `use_packrat()` - Set up packrat for the project
-  `use_rrtest()`  - Use the **rrtools** testing framework.

## CI

-   Install dependencies
-   Run build scripts
-   Produce testing artifacts
-   Deploy - back to the repo or to an outputs/docs branch?
-   What do we want from production environments, and what do we discard?

## Review/documentation

-   Reviewing the tests
-   Main output as a manuscript-like thing
-  Actual manuscript may not be held in repo
   -   Main report can be some kind of output that contains essential figs/values
   
## What can we learn from existing tools?

-   https://www.yhat.com/products/bandit
-   https://empiricalci.com/

![](https://upload.wikimedia.org/wikipedia/commons/f/fd/Ghostscript_Tiger.svg)
