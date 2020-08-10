# Material for the session "Introduction to Deep Learning in R for the analysis of UAV-based remote sensing data"

*OpenGeoHub summer school 2020*


# Installation

Install a current version of R and the following packages:

`install.packages(c("keras","tfdatasets","mapview","stars","rsample","gdalUtils","purrr", "magick", "jpeg"))`

Install miniconda, keras and tensorflow python dependencies:

- `reticulate::install_miniconda()`
- `keras::install_keras()`

For installing dependencies of rgdal, stars and magick on linux:

- gdal:`sudo apt-get install gdal-bin libgdal-dev`

- stars: `sudo apt-get install libudunits2-dev`

- magick: `sudo apt-get install libmagick++-dev`
