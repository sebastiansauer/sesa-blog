+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
draft = false
author = Sebastian Sauer
tags = []
categories = []
output:
  blogdown::html_page:
    toc: true
+++



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



# Vorbereitung

```{r load-libs, message = FALSE, warning = FALSE}
library(tidyverse)  # Datenjudo
```






# Reproduzierbarkeit

```{r reproducibility, echo = FALSE}

options(width = 120)
devtools::session_info()


