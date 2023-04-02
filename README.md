# multilingual-nlp

This repository contains sample pipelines from processesing Arabic and Chinese corpora. To use the repository:

1. Be sure to have [R and R Studio installed](https://posit.co/download/rstudio-desktop/).
2. Download or clone the repository
3. Intall the `devtools` R package
4. Install `cmu.textstat` by following [the instructions here](https://github.com/browndw/cmu.textstat)
5. Open the R Project file called `multilingual-nlp.Rproj` in the root folder of the downloaded or cloned repository

Once you have opened to R project, you can navigate to one of the notebooks -- either `udpipe_arabic.Rmd` or `udpipe_chinese.Rmd` which are in the folder named `R`. Note that you should do this **from the Project**. If you're not sure how to navigate R Studio or a Project, lots of help is available:

* [Programming With R | Navigating RStudio](https://www.youtube.com/watch?v=I0qNSNt8Vmc)
* [RStudio Projects and Working Directories: A Beginner's Guide](https://martinctc.github.io/blog/rstudio-projects-and-working-directories-a-beginner%27s-guide/)
* [RStudio projects](https://www.youtube.com/watch?v=YGT1tI_i_Po)

You can then run the code in the notebooks. For additional support and help, you can refer to the documentation for:

* [`cmu.textstat`](https://cmu-textstat-docs.readthedocs.io/en/latest/quanteda.extras/vignettes/collocations_introduction.html)
* [`quanteda`](http://quanteda.io/)
* [`udpipe`](https://cran.r-project.org/web/packages/udpipe/vignettes/udpipe-annotation.html)
