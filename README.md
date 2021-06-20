# BIOS - _Tidy modeling_

This repo contains a presentation and summary with short exercises. The 
content is based on __chapters 4--7__ from the book by Max Kuhn and Julia Silge
[_"Tidy modeling with R"_](https://www.tmwr.org/).

## Requirements

To run the code in `tidy_models_part2.Rmd`, you need to install the following
packages:

- [`tidymodels`](https://www.tidymodels.org/)
- [`tidyverse`](https://www.tidyverse.org/)
- [`skimr`](https://docs.ropensci.org/skimr/)
- [`patchwork`](https://patchwork.data-imaginist.com/index.html)
- [`usemodels`](https://usemodels.tidymodels.org/)

In addition, to _knit_ the .Rmd file, you need these packages:

- [`knitr`](https://yihui.org/knitr/)    
_(automatically installed with RStudio!)_
- [`rmarkdown`](https://rmarkdown.rstudio.com/lesson-1.html)    
_(automatically installed with RStudio!)_
- [`rmdformats`](https://github.com/juba/rmdformats#installation)
- [`fontawesome`](https://rstudio.github.io/fontawesome/)

To install all of those, copy the following command to R-console (or click on
"Install" in the banner that appears when opening the .Rmd file in RStudio):

```{r}
install.packages(c("tidymodels", "tidyverse", "skimr", "patchwork", "usemodels",
                  "knitr", "rmarkdown", "rmdformats", "fontawesome"))
```

## Viewing the presentation

Presentation is created in .Rmd, using [`xaringan`](https://github.com/yihui/xaringan),
[`xaringanthemer`](https://pkg.garrickadenbuie.com/xaringanthemer/),
and [`xaringanExtra`](https://pkg.garrickadenbuie.com/xaringanExtra/#/README?id=xaringanextra)
packages. The compiled output is in the `JRom_tidy_models_part2_pres.html` file.
To view it, open the file from your disk, using your internet browser.

> You need to download or clone the entire repository to view all the figures
> and to enjoy the nice .html style!

To view the source code, open the accompanying .Rmd file in RStudio.
