---
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
draft = false
tags = [rstats]
categories = []
output:
  blogdown::html_page:
    toc: true
    number_sections: TRUE
---


```{r setup, echo = FALSE, message = FALSE, warning = FALSE}
## Load frequently used packages for blog posts
library('knitcitations')  # for citations
library('devtools')  # for session_info()
library('tidyverse')  # for data_wrangling
library('BiocStyle')  # for CRANpkg() Biocpkg() Githubpkg()


## Load knitcitations with a clean bibliography
cleanbib()
cite_options(hyperlink = 'to.doc', citation_format = 'text', style = 'html')

bib <- c(
    'blogdown' = citation('blogdown')[2],
    'devtools' = citation('devtools'),
    'knitcitations' = citation('knitcitations')
)
```


```{r knitr-setup, echo = FALSE}
knitr::opts_chunk$set(
  comment = "#>",
  collapse = TRUE,
  message = FALSE,
  warning = FALSE,
  cache = TRUE,
  out.width = "100%",
  fig.align = 'center',
  fig.width = 6,
  fig.asp = 0.618,  # 1 / phi
  fig.show = "hold",
  size = "tiny"
)
```






### Acknowledgements


This blog post was made possible thanks to:

* `r CRANpkg('blogdown')` `r citep(bib[['blogdown']])`
* `r CRANpkg('devtools')` `r citep(bib[['devtools']])`
* `r CRANpkg('knitcitations')` `r citep(bib[['knitcitations']])`





### References

```{r bibliography, results = 'asis', echo = FALSE, cache = FALSE}
## Print bibliography
bibliography(style = 'html')
```




### Reproducibility

```{r reproducibility, echo = FALSE}
## Reproducibility info
options(width = 120)
session_info()
```
