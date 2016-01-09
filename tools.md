tools
=====

The course tought by professor [Holt](mailto:ginger.koev@northwestern.edu) will feature R specifically. I'll be working in [Fedora 23](https://en.wikipedia.org/wiki/Fedora_(operating_system)) during this semester and will be using [R-Studio](https://en.wikipedia.org/wiki/RStudio) as a development environment.

# R and R-Studio

    wget https://download1.rstudio.org/rstudio-0.99.491-x86_64.rpm
    md5sum rstudio-0.99.491-x86_64.rpm  # should match 0c02d3ec5d69e43ea0e32a3d8de443f4
    sudo dnf install R R-devel
    sudo dnf install rstudio-0.99.491-x86_64.rpm

From here you will be able to use R-studio to install packages from [CRAN](https://cran.r-project.org/).

The Libraries used in the course are:

 - [quantmod](http://www.quantmod.com/)
 - [fbasics](https://www.rmetrics.org/)
