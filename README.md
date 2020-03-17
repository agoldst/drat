# drat repository

Releases for my R packages hosted on github. To use, install the [drat](https://cran.r-project.org/web/packages/drat) package and add this repository as follows:

```r
if (!require("drat")) {
    install.packages("drat")
    library("drat")
}
drat::addRepo("agoldst")
```

Then `install.packages("dfrtopics")` (etc.) ought to work.

# R packages hosted here

- [dfrtopics](https://github.com/agoldst/dfrtopics). Explore topic models.
- [mlaibr](https://github.com/agoldst/mlaibr). Wrangle bulk-exported MLA International Bibliography data.
- [scuro](https://github.com/agoldst/scuro). RMarkdown presentation format.

