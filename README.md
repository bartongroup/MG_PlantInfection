# How are Phytophthora effectors taken into plant cells?

Collaborators: Paul Birch, Haixia Wang

The code to perform minor statistical analysis for [Wang et al. "Uptake of oomycete RXLR effectors into host cells by clathrin-mediated endocystosis" (2023), *Plant Cell*, 35, 2504](https://academic.oup.com/plcell/article/35/7/2504/7076388).

## Instructions

The code and text are in `doc/analysis.Rmd` document. The first step is to create environment using `renv`:

```
install.packages("renv")
renv::restore()
```

This will install all necessary packages. Then, the document can be parsed

```
rmarkdown::render("doc/analysis.Rmd")
```

This will carry out all the calculations and create a document `doc/analysis.html`.
