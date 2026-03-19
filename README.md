# Pilot DB with Mareano

[![DOI](https://zenodo.org/badge/1161573065.svg)](https://doi.org/10.5281/zenodo.19109005)

This repository contains the source Quarto Markdown documents for the [Pilot DB with Mareano](https://seafood-hazards.github.io/pilot-db-with-mareano/) website.

## License
This project is licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

## Data source
The original chemical data used in this project is available on the [Mareano Chemical Data](https://www.mareano.no/en/maps-and-data/chemical-data) page.

## Development
The website is automatically generated and deployed using a dedicated GitHub workflow, but it can also be build manually. The site is based on [Quarto](https://quarto.org/) using R, with dependent R packages managed by [renv](https://rstudio.github.io/renv/). The following commands set up an R environment for the project.

```R
renv::activate()
renv::update()
```

Then, the easiest approach is to use Rstudio, which provides a ``Render Website`` option in the ``Build`` menu.
