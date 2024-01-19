# Plotting in R Animal Science Book

<!-- badges: start -->

<!-- badges: end -->

This repository contains a crash-course for animal scientists looking to efficiently visualize their data. It is designed to accompany an in-person workshop, so it does not cover all the basics of using R, and there are better resources available for learning R thoroughly.

The focus of this 'book' is on data wrangling and plotting, excluding statistical concepts. The techniques presented aim to promote the reproducibility of work. Keeping well-documented code enables the easy recreation of scientific outputs from the original raw data.

## Getting Started - developers

This book is built using Quarto. To use the source code for this book, clone it to your local machine and activate the `renv` environment to download required packages:

``` bash
# Clone the repository
git clone https://github.com/CNM-University-of-Guelph/Plotting-in-R-Animal-Science-Book.git
```

Open the project in RStudio and activate `renv`:

``` r
# Activate the renv environment
renv::restore()
```

## Preview and render

The page can be rendered for development calling the following in a terminal (at same directory to this repo). This will spin up a local html server that updates in real-time as changes are saved.

``` bash
quarto preview
```

A whole `_book` directory can be created with the final rendered website by calling:

``` bash
quarto render
```

## Deploy to GitHub

`quarto publish` is the preferred method of deploying to GitHub pages. This will automatically render the book, commit it to a branch called gh-pages and the copy those files to the GitHub pages URL associated with this repo. More details [here](https://quarto.org/docs/publishing/github-pages.html#publish-command)
