---
title: "R"
weight: 4
subtitle: ""
excerpt: "R and the RStudio IDE"
draft: false
---

## Remote sources

**R** itself can be installed with homebrew:

```
brew install r
```

**RStudio IDE** is amazing, download from [here](https://www.rstudio.com/products/rstudio/download/), and follow chief scientist [Hadley Wickham](https://twitter.com/hadleywickham) for latest developments in the tidyverse.

## Configuration
.Renviron (store API keys here) and .Rprofile files (R code that runs each time on startup)

Best to have all packages explicitly called by `library()` at the start of each script, rather than relying on them being in .Rprofile and hence losing reproducibility for other users.  The similar function `require()` returns a boolean not an error so can be useful in a try/catch style flow.

To manage a github repo as an project in R-Studio (e.g. with ```Hugo```) clone the repo **from within RStudio**, using ```New Project``` @fa-arrow-circle-right ```Version Control```

## Packages
**tidyverse**
