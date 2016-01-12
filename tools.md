tools
=====

The course tought by professor [Holt](mailto:ginger.koev@northwestern.edu) will feature R specifically. I'll be working in [Fedora 23](https://en.wikipedia.org/wiki/Fedora_(operating_system)) during this semester and will be using [R-Studio](https://en.wikipedia.org/wiki/RStudio) as a development environment.

# R, R-Studio, Jupyter

R-Studio gives a very nice front end for R, its a fall-back for me though as I'll work hard to use Jupyter within this course.

    wget https://download1.rstudio.org/rstudio-0.99.491-x86_64.rpm
    md5sum rstudio-0.99.491-x86_64.rpm  # should match 0c02d3ec5d69e43ea0e32a3d8de443f4
    sudo dnf install R R-devel
    sudo dnf install rstudio-0.99.491-x86_64.rpm

From here you will be able to use R-studio to install packages from [CRAN](https://cran.r-project.org/).

The Libraries used in the course are:

 - [quantmod](http://www.quantmod.com/)
 - [fbasics](https://www.rmetrics.org/)

I'll be attempting to do all the assignments in Jupyter notebooks. The least clunky way to do this is to use Anaconda from Continuum Analytics. Acquire the software [here](https://www.continuum.io/downloads), then there is a solid guide [here](http://conda.pydata.org/docs/index.html) on using conda.

To get R working in a notebook we'll do the following:

    conda install --channel r r-essentials
    conda create --name 413 --channel r r-essentials
