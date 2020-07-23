# PlotXpress

<!-- badges: start -->
[![CRAN](https://www.r-pkg.org/badges/version/shiny)](https://CRAN.R-project.org/package=shiny)
[![R build status](https://github.com/rstudio/shiny/workflows/R-CMD-check/badge.svg)](https://github.com/rstudio/shiny/actions)
[![RStudio community](https://img.shields.io/badge/community-shiny-blue?style=social&logo=rstudio&logoColor=75AADB)](https://community.rstudio.com/new-topic?category=shiny&tags=shiny)

<!-- badges: end -->

 
PlotXpress is a shiny app that simplifies the analysis and plotting of data from a dual luciferase experiment in 96-well format.

## Input data (expressed as arbitrary luminescence units)
* Excel sheet containing 2 tables in 96-well lay-out (raw output from a Promega GloMax® Navigator). An unprocessed example output file is included: `DualLuc_example_data.xlsx`
* An excel file or CSV file in which conditions are indicated in a 96-well lay-out. The conditions are seperated by underscores (see the example design that is included in this repo: `Design_example.xlsx`)

### Example output

Standard output generated with the example data:

![alt text](https://github.com/ScienceParkStudyGroup/PlotXpress/blob/master/plotXpress_example.png "Output")

### Credits

<p>The plotXpress app is created as a team effort by Elias Brandorff, Marc Galland & Joachim Goedhart</p>

### Contact

Questions related to the shiny app can be addressed to: Joachim Goedhart ([@joachimgoedhart](https://twitter.com/joachimgoedhart))