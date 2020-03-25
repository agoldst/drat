---
layout: default
---

This is a [drat](https://cran.r-project.org/web/packages/drat) repository for [Andrew Goldstone](https://andrewgoldstone.com)'s R packages on github. It allows you to install and update those packages via the same mechanisms you use for CRAN packages. 

To use, install the [drat](https://cran.r-project.org/web/packages/drat) package and add this repository as follows:

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
- [scuro](https://github.com/agoldst/scuro). Create RMarkdown presentations and articles with some typographical features.

