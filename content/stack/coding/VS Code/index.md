---
title: "VS Code"
weight: 2
subtitle: ""
excerpt: "Text editor, IDE"
---
Microsoft has bought GitHub, and hence also the text editor Atom. VS Code is a similar free, open-source in-house Microsoft product, and as at 2021 development efforts (for example Julia) seem to be favoured here.  

## Pre-requisites

VS Code can be downloaded from 

```
install.packages("blogdoown")
```

Restart your R session. If you use RStudio, use the menu item *Session > Restart R* or the associated keyboard shortcut:

+ <kbd>Ctrl + Shift + F10</kbd> (Windows and Linux) or
+ <kbd>Command + Shift + F10<kbd> (Mac OS). 

```
packageVersion("blogdown")
[1] ‘1.0’
```

## Create GitHub repo

Online.

## Clone GitHub repo

```
usethis::create_from_github("https://github.com/apreshill/global-blogdown.git")
```

:sparkles: Commit & Push! :sparkles:

You should be committing these files:

+ `*.Rproj`

+ `.gitignore`

## Create a new blogdown site

We'll be using a new Hugo theme that I made for us! 

Inside your current blogdown project, use the R console:

```
library(blogdown)
```

Let's start with making the website with the theme: 

```
new_site(dir = ".", theme = "apreshill/blogophonic")
```

## Configure your site

The first stop on this tour of your site is the `config.yaml` file.


