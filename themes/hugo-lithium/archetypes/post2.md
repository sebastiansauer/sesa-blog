---
title: ''
date: ''
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



# Load packages

```{r load-libs, message = FALSE, warning = FALSE}
library(tidyverse)  # data wrangling
```






# Reproducibility

```{r reproducibility, echo = FALSE}
## Reproducibility info
options(width = 120)
devtools::session_info()


