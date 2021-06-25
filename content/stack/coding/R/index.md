---
title: "R"
weight: 1
subtitle: ""
excerpt: "R and the RStudio IDE"
draft: false
---

## Remote sources

R itself can be installed with homebrew:

```
brew install r
```

RStudio IDE is amazing, [download page](https://www.rstudio.com/products/rstudio/download/), follow chief scientist [Hadley Wickham](https://twitter.com/hadleywickham) for latest developments in the tidyverse 

## Configuration
.Renviron (store API keys here) and .Rprofile files (R code that runs each time on startup)

Best to have all packages explicitly called by `library()` at the start of each script, rather than relying on them in Rprofile and hence losing reproducibility.  The function `require()` returns a boolean not an error so can be useful as try/catch.

## Some useful packages
**tidyverse**
