# drat repository

Releases for my R packages hosted on github. To use, install the [drat](https://cran.r-project.org/web/packages/drat) package and add this repository as follows:

```r
if (!require("drat")) {
    install.packages("drat")
    library("drat")
}
drat::addRepo("agoldst")
```

Then `install.packages("dfrtopics")` (etc.) ought to work. Available packages are listed at <https://agoldst.github.io/drat>.
