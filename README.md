# Intro to ggplot2

## Setup

You will need to install software in order to participate in this workshop. The software is:

- [R](https://www.r-project.org/) (a statistical programming language)
- [RStudio](https://www.rstudio.com/) (a development environment for R)
- [tidyverse](https://www.tidyverse.org/) (we'll import this through RStudio)

These tools are available across platforms. You do not need specific computers to use it.

Please also download the workshop dataset:

- Link here

## What is ggplot2?

ggplot2 is a data visualization library for the statistical programming language R. It is part of a larger group of libraries called the tidyverse.

ggplot2 lets you visualize data in R, making it a good choice for people who want to visualize data in the same program they analyze it in. It saves you time and connects directly to your data.

## Getting started

To begin, we need to import ggplot2. Open RStudio.

If you are installing ggplot2 for the first time, type ``install.packages('tidyverse')``. This will install ggplot2, as well as every library in the tidyverse. (If you don't want to install the entire tidyverse, you can also enter ``install.packages(ggplot2)``.)

If you have already installed ggplot2, you will need to load it so that your session of R recognizes that you will be using it. Type the command ``library(ggplot2)``.

We will also need to load data. Use the data included in the workshop files.

``dataname <- read.table(file = "dataname.csv", header = TRUE, sep = "\c")``

## License

You are free to use, re-use, or re-mix this material for academic, educational, or non-profit purposes. If you have questions, please contact me.
