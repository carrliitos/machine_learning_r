# Machine Learning in R

A self-study notebook for the *penalized linear regression* model using *elastic nets* for the penalization or 
regularization.

YouTube video can be found here:
[Machine Learning in R Part 1: Jared Lander](https://youtu.be/WWuW4kkI_SA)

## Execution
To execute, run the below commands:

```{r}
rstudioapi::jobRunScript(here::here("execute.R"))
```

If RStudio is not running, open an R terminal and run the following:

```{r}
source(here::here("execute.R"))
```

## Structure
The project contains the following general structure:

## Structure
The project contains the following general structure:

* [R](./R): Complex or significant amounts of R code that is not appropriate for notebooks.
* [data-raw](./data-raw): Incoming datasets that should be considered readonly.
* [data](./data): Datasets produced for cleaning, analysis, or distribution after execution of scripts.
* [notebooks](./notebooks): Notebooks that support the manipulation and analysis of the datasets; number workbooks in order of execution required and divide into subdirectories if needed.
* [output](./output): Any documents or datasets intended for distribution from this project.
* [renv](./renv): R packages needed to execute the project.
* [reports](./reports): RMarkdown documents that support the manipulation and analysis of the datasets; number workbooks in order of execution required and divide into subdirectories if needed.
* [sql](./sql): SQL scripts to extract datasets.
