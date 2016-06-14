# Two Perspectives on Literate Programming with R Markdown

Training materials for a 60 minute session on reproducible analysis and deliverables using R Markdown. Includes slides, exercises, and examples. 

To follow along with this session and complete the exercises, you'll need: 

- R
- RStudio
- The following set of packages:

```{r}
pkgs <- c('knitr', 'rmarkdown', 'dplyr', 'ggplot2', 'readr', 'lubridate', 'tidyr', 'nycflights13')
install.packages(pkgs)
install.packages('flexdashboard', type = 'source')
```

You can install these packages by opening RStudio, and copying and pasting the code above into the console, and hitting "Enter".

These materials assume minimal experience in the R language itself. You don't need to be an R expert to follow along, but some R skills (especially visualization) will help you get the most out of them. 