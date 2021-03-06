# 📚 🛠 Tutorial proposal

Submission via the [useR! 2022](https://user2022.r-project.org/) abstract submission system by Tuesday, January 31, 2022.

Please read the [code of conduct](https://user2022.r-project.org/about/coc/) before the start of the tutorial.

#### Format preferences:

- virtual, morning/afternoon, length 2 hours and a half

#### Language in which the tutorial will be taught:

- English

***

## Title: *Visualization of spatial data models: from theory to practice*

***

## A brief biography of the instructors:


**Simina Boca** is a Biostatistician in Early Biometrics & Statistical Innovation, Data Science & Artificial Intelligence, R & D, AstraZeneca. Her interests include exploratory data analysis and data visualization, high-dimensional analysis, and data integration.


**Federica Gazzelloni** is a Statistician and an Actuary with interest in Advanced Statistical Methods for data modeling, in public health. She is a collaborator of the IHME for the GBD studies. Her volunteering activity with the R4DS community involves practicing using R for teaching and making data visualizations.


## The broad topic it covers

The application of basic modeling techniques to spatial data for making beautiful maps will empower users knowledge and ability in making useful data visualizations. In addition, to become able to present data evolution through map visualizations will improve the strength on making advanced analysis, and reducing the time consuming in understanding spatial applications but selecting just the important features for the scope.

The competition of this tutorial will enable the participants to:

- Manage data for making spatial analysis
- Apply modeling techniques for spatial analysis
- Make a spatial model visualization



## Abstract

A visualization of spatial data modeling will be presented. The data are selected from the {SpatialEpi} package which includes statistics on cancer cases in a number of locations, including Scotland, New York, and Pennsylvania.
The data sets contain the number of cases, the expected values as well as the geo-data with the latitude, longitude, and polygons for representing the geometry of the locations to be used for making a map.
A visualization of a spatial model involves making a model of the coordinates for predicting an outcome. This type of technique can be used for several purposes. For this tutorial cancer data will be used, with the aim to understand the pattern of a disease through a map of the observed cases versus the number of predicted cases.
In this tutorial, a simple linear model will be presented for educational purposes and to make the approach to spatial modeling straightforward for all the users.
The tutorial will also focus on using {ggplot2} package for spatial data, highlighting basic differences with other packages. To conclude, additional visualization features from the {cowplot} package will be discussed and the final visualization will be saved as .png file.



## Intended audience and prerequisites

### Audience:

The tutorial is for users with more than one year of continual experience, who are interested in spatial model visualizations.


### Prerequisites:

-	Knowledge of different R data types & structures such as the difference between numeric and character values, what is a data frame and a vector, etc.

-	Knowledge of the difference between the base and the {ggplot2} approaches to data visualizations.

-	Basic knowledge of modeling with R, such as what is a model, why models are useful, what is an outcome and a predictor.

-	Basic knowledge of a GitHub repository, such as how to get access to data, etc.


### Computing requirements:

Participants should have a laptop with access to the internet. Installation of R is not required but recommended; the participants can use RStudio Cloud workspace. 

#### Required R Packages:

- {SpatialEpi} package of methods and data for spatial epidemiology
- {tidyverse} which include {ggplot2} for making data wrangling and visualizations
- {maps}, {tmap}, {sf}, {rnaturalhearth} for spatials
- {tidymodels} for modeling
- {patchwork}, {cowplot} and {ragg} for final touches of the visualization


## A brief outline of the tutorial

### Session 1 (40 minutes): Manage data for making spatial analysis

- Introduction of the tutorial and the instructors, biographies and the course content that will be used during the course (such as the GihHub repository, the data to use)
- Introduction to spatial data with {ggplot2} with a visualization of a map made from a dataset selected from {SpatialEpi} package.
- Advice on different packages for making the same visualization, such as {maps},{sf},{tmap}.

**Break 15 minutes & QA**

### Session 2 (40 minutes): Apply modeling techniques for spatial analysis

- Introduction to modeling with RStudio, base R modeling, liner models structure 
- Advice on how to use {tidymodels} for eventually use different types of models
- Example of spatial model

**Break 15 minutes & QA**

### Wrap-up (10 minutes): Make a spatial model visualization

🎣 Make the map visualization, add final touches with {cowplot} and save it as .png file.

### Participants Pratice session (30 minutes):

- Access to the GitHub tutorial repository: https://github.com/Fgazzelloni/tutorials
- Load the data from {SpatialEpi} package
- Apply the code taught in the previous sessions
- Save the work on a .png file

## Link to the tutorial materials:

- https://github.com/Fgazzelloni/tutorials

