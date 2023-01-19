# BST 270 Individual Project

This repository contains my attempt to reproduce tables/figures from FiveThirtyEight's [2022 World Cup Predictions](https://projects.fivethirtyeight.com/2022-world-cup-predictions/). 

## Setting up the compute environment

This project uses the R programming language. Package management is handled through the `pacman` R library and ought to work on various versions of R and the `pacman` library for the forseeable future. Just to be safe, you can recreate my exact computing environment by setting up a [conda](https://quarto.org/docs/get-started/) environment using the provided `environment.yml` file:

```
conda env create -f environment.yml
```

## Project Structure

The entire reproduction attempt is located in `./code/reproduction.Qmd`. `.Qmd` is the [Quarto](https://quarto.org) file extension and can be compiled from the command line or a handful of text editors, including RStudio and VSCode (which I use) -- see [here](https://quarto.org/docs/get-started/) for options. Quarto documents, like RMarkdown, can compile into a variety of document types -- I've included an html version of my final reproduction attempt in the `./code` directory.

This repo comes with an empty `./data` directory, which will be populated with two small data sets the first time `reproduction.Qmd` is run. 
