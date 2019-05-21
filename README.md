# My first test repo

Hello World!

Extra things here.

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, cache = TRUE, dpi=300)
```

```{r test}
if (!require("pacman")) install.packages("pacman")
pacman::p_load(tidyverse, broom, hrbrthemes, plm, estimatr, sandwich, lmtest, AER, lfe, huxtable, margins)
theme_set(hrbrthemes::theme_ipsum())
```