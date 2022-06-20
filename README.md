# Intro to ggplot2

Welcome! This workshop will introduce you to [ggplot2](https://ggplot2.tidyverse.org/), a library for data visualization in R.

Some of what you will learn includes:
- geom functions
- aes functions
- categorical vs. continuous variables and why they matter

ggplot2 follows what a "grammar of graphics."

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

##

## Getting started

To begin, we need to import ggplot2. Open RStudio.

If you are installing ggplot2 for the first time, type ``install.packages('tidyverse')``. This will install ggplot2, as well as every library in the tidyverse. (If you don't want to install the entire tidyverse, you can also enter ``install.packages(ggplot2)``.)

Once you have installed ggplot2, load it using the command ``library(ggplot2)``. (You'll need to do this every time you start a new session in R!)

We will also need to do the same for our data. We are using a dataset that comes with ggplot2, called ``mpg``.

## Exploring ggplot2

Now that our data is loaded, what can we do with ggplot2?

Luckily, there's a command just for that. Type ``?ggplot2``.

You can use this command for any library in R (just substitute "ggplot2" for the name of your library). Using this command, we can see that ggplot2 comes with documentation.

## Anatomy of a ggplot2 command

ggplot2 is grounded in what its developers call a grammar of graphics. We don't have time today to delve into what this means, but we can use the phrase as a way to understand how its commands are structured.

Let's say that we want to see how many photographers featured at the Carnegie Museum of Art are from Canada. We can do this with the command ``ggplot2(aes = )``

## Continuous and categorical variables



## Resources for further learning

<<<<<<< Updated upstream
ggplot2 Cheat Sheet  
*R for Data Science*  
R-Ladies  
=======
[ggplot2 Cheat Sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-visualization.pdf)  
*R for Data Science*  
R-Ladies - group for women and gender minorities using R  
>>>>>>> Stashed changes

## License

You are free to use, re-use, or re-mix this material for academic, educational, or non-profit purposes. If you have questions, please contact me.

## Contact

You can contact me via email at [shiloh.williams@brocku.ca](mailto:shiloh.williams@brocku.ca) or via Twitter at [@shilowil](https://www.twitter.com/shilowil).
