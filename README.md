# How are Phytophthora effectors taken into plant cells?

Collaborators: Paul Birch, Haixia Wang

The code to perform minor statistical analysis for Wang et al. (2023), accepted by The Plant cell.

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
