# Heart Disease Analysis

This repository contains the project I've developed for the final exam of the course "Fundamentals of Data Science" at the [University of Udine](https://www.uniud.it/it) held by [Massimo Franceschet](https://users.dimi.uniud.it/~massimo.franceschet/ds/plugandplay/ds.html).

## Description

I chose to work on a medical dataset I found on [Kaggle](https://www.kaggle.com/) named [Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci) which provides values for 14 different attributes observed in 303 patients. The aim of the analysis was determining the influence of different diagnostical factors in the occourence of cardiovascular diseases.

I've also been able to train a Logistic Regressor to predict cardiovascular diseases in patients with an accuracy degree of 80%. This lead me to some reflections on how Machine Learning and Data Science might become useful tools for physiciants in the future, if used ethically. 

## Who provided the dataset

The dataset used has been provided by the following clinics and universities:

- **Hungarian Institute of Cardiology**. Budapest: Andras Janosi, M.D.
- **University Hospital, Zurich, Switzerland**: William Steinbrunn, M.D.
- **University Hospital, Basel, Switzerland**: Matthias Pfisterer, M.D.
- **V.A. Medical Center, Long Beach and Cleveland Clinic Foundation**: Robert Detrano, M.D., Ph.D.


## Tools used

I used [RStudio](https://rstudio.com/) as my working environment and I wrote my analysis in [RMarkdown](https://rmarkdown.rstudio.com/). I even wrote a few slides (again, in RMarkdown using [ioslides presentation](https://bookdown.org/yihui/rmarkdown/ioslides-presentation.html) template) that I used during the final presentation. However, slides contain only a subset of the overall analysis because I had to respect a 15 minutes limit.

As requested by the assignement, I wrote the natural language part of both the analysis and slides in **Italian**. However, I tried to be careful on using meaningful variable names and using English comments in order to let you understand the code by itself.

## Repository's Structure

The actual repository contains the following files: 

- **data** (directory for data-related files)
	+ `heart2.csv` (the Heart Disease UCI dataset used)
	+ `info_dataset.txt` (A txt file i compiled with additional infos on dataset variables)
- **img** (directory that contains all the images used for the report)
- `scrollable_slides.css` (a custom CSS file that allows slides to be scrollable)
- `heart.Rmd` (the Rmd file that contains the analysis)
- `slides.Rmd` (the Rmd file that contains the slides)

In order to build the full report as a markdown or HTML file you need to open the analysis file in RStudio and export it in your favourite format. It will take a few minutes.

## A quick look at the final result

If you're interested in how the final result looks like, even if in Italian language, you can take a quick look at the report directly exported from RStudio at [this link](http://latoserver.dimi.uniud.it/~twc20_cantarutti/other/heart/). You can also access the slides directly [here](http://latoserver.dimi.uniud.it/~twc20_cantarutti/other/heart/Presentation.html#1).


