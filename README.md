# Project-5
Group 5 project for STAT400 @ CSU

# Group Members
Austin Lackey, Chien Lin and Jin Peng

# Background Information

## The study we replicated

**Mathematical prediction of the time evolution of the COVID-19 pandemic in Italy by a Gauss error function and Monte Carlo simulations**

<br>

*Author: Ignazio Ciufolini, Antonio Paolozzi*

## What we did
* The time evolution of the number of cumulative diagnosed positive cases and fatalities in China approximates the distribution of a gauss error function: $a+b*erf(c*x-d)$.
* Performed the function on Italy data to approximate the number of cases.
* Performed 150 Monte Carlo simulations to predict the day in which the peak of the number of daily cases in Italy occurs.

# Directions

## Install Packages
### Ensure the neccesary packages are installed, see the list below...

* tidyverse
* pracma
* minpack.lm

*Note:* If you do not have one of these packages installed. use the command `install.packages("<package-name>")` to install it.

# Paper
### Run/Knit the *"paper.rmd"* file and a **"paper.pdf"** should export.

# Presentation
### Run/Knit the *"powerpoint.rmd"* file and a **"powerpoint.pptx"** powerpoint should export.

# Works Cited

- Link to the study:
  - I. Ciufolini, A. Paolozzi, Prediction of the time evolution of the Covid-19 Pandemic in Italy by a Gauss
Error Function and Monte Carlo simulations. Submitted to BioRxiv on 03.26.2020 and transferred on
03.27.2020 to MedRxiv. https://doi.org/10.1101/2020.03.27.20045104
- Link to the covid data used:
  - https://covid19.who.int/
- Source to find the second derivative of fitted function:
  - https://proofwiki.org/wiki/Derivative_of_Error_Function