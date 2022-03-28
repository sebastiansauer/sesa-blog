---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: Sebastian Sauer
date: {{ .Date }}

tags: {{ .Tags }}
categories: []


draft: true

output:
  blogdown::html_page:
    toc: true
    keep_md: yes
---




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

```



