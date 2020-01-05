# Code for "Trade, migration, and the dynamics of spatial interaction"

[![CircleCI](https://circleci.com/gh/nick-gauthier/trade-migration.svg?style=svg)](https://circleci.com/gh/nick-gauthier/trade-migration)  [![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nick-gauthier/trade-migration/master?urlpath=rstudio)

This repository contains the working files of data and code for our paper:

> Gauthier, N. (2019). *Trade, migration, and the dynamics of spatial interaction*. SocArXiv
> <https://doi.org/10.31235/osf.io/trbf8>

The files that produced the published results are also archived at <xxx>

### How to cite

Please cite this compendium using the archival URL (and not a GitHub URL):

> Gauthier, N. and Marwick, B., (2019). *Compendium of R code for ‘Trade, migration, and the dynamics of spatial interaction’*.
> Accessed 15 Nov 2018. Online at <xxx>

### How to view, run, download

You can view the results of the analysis online here: <https://github.com/nick-gauthier/trade-migration/blob/master/manuscript/Gauthier_TradeMigration.pdf>

You can run the code in your browser (no download or install required) by [launching Binder](http://beta.mybinder.org/v2/gh/nick-gauthier/trade-migration/master?urlpath=rstudio)

You can download the compendium as a zip from this URL:
<https://github.com/nick-gauthier/trade-migration/archive/master.zip>

You can get the complete computational environment used for this project with our Docker container. To launch the Docker container for this project, first, install Docker on your computer. At the Docker prompt, enter:

```
$ docker run -dp 8787:8787 -e PASSWORD=rstudio -e ROOT=TRUE nickgauthier/trade-migration
```

Then open your web browser at `localhost:8787` or or run `docker-machine ip default` in the shell to find the correct IP address, and log in with rstudio/rstudio. More information about using RStudio in Docker is avaiable at the [Rocker wiki](https://github.com/rocker-org/rocker/wiki/Using-the-RStudio-image) pages.

