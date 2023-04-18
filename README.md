
# Data Analysis Project Template

<!-- badges: start -->
<!-- badges: end -->

This is a data analysis project template that I developed for students in my QTM/ENGRD 302W: Technical Writing for Data Science course, at Emory University, to put reproducibility concepts into practice (see Marwick et al. 2018; Moncrieff 2020).

The template provides you with a basic directory structure for your research project, from which you can create your own repository here on GitHub to clone to your own computer. Moreover, it contains instructions on using the package renv to manage a virtual environment with your project's package dependencies. Further, it walks through preparing your repository to work with [mybinder.org](https://mybinder.org), making use of the [holepunch package](https://karthik.github.io/holepunch/articles/getting_started.html) to generate the necessary files. You can read through this tutorial by clicking on `reproducibility.md` above.

## Getting Started

1. Click the green "Use this template" button in the upper-right-hand corner of the screen. From there, select "Create a new repository." Give it a good descriptive name for your project.

2. Clone your new repository to your computer that has R and Studio installed. You can do this in a number of ways: 
  - Using the [command line](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) 
  - From within RStudio, by selecting the "Version Control" option when Creating a New Project, and then "Clone a project from a Git repository" 
  - Using [GitHub Desktop](https://desktop.github.com). After installing, you can click the "Code" button on your repository page and open it in GitHub Desktop from there. Otherwise, you can follow the [instructions here](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop). 
  
3. Rename the `.Rproj` file for your purposes and open it in RStudio.

4. In the Files pane, open `reproducibility.Rmd` and follow along inside the document.

5. After you do, delete or move `reproducibility.Rmd`, `reproducibility.md`, and the directory `inst` before committing and pushing your local repo back to GitHub.
  

## Works Cited

Marwick, B., Boettiger, C., L. Mullen, L. (2018), “Packaging Data Analytical Work Reproducibly Using R (and Friends).” The American Statistician 72 (1): 80–88. https://doi.org/10.1080/00031305.2017.1375986.

Moncrieff, G. (2020), "Reproducible R part 1." https://rstudio-pubs-static.s3.amazonaws.com/599947_7c545f28e24e4d21ab5dcbbb59210c63.html.

Ram, K. (2023), holepunch: Make your R project Binder ready. R package version 0.1.29.9000. https://github.com/karthik/holepunch/
