# Fundamentals of Simulation Project

## Overview
This project demonstrates the concept of confidence interval coverage through simulation. The primary goal was to illustrate how a (1 – α)100% confidence interval performs for estimating parameters under repeated sampling. This was completed as the term project for a fundamentals of simulation course, with all analysis implemented in R.

## Repository Contents
*   **`DSCI 3411 Project Code.Rmd`**: The R Markdown source file containing the simulation code and narrative.
*   **`DSCI-3411-Project-Code.html`**: The compiled HTML output of the R Markdown file, showing code and results.
*   **`DSCI 3411 Project Report.pdf`**: The final project report detailing the methodology and findings.
*   **`Alternative File of the Code [R Script]`**: An alternative R script version of the simulation code.

## Key Methods and Techniques
*   **Simulation**: Designing and running Monte Carlo simulations to generate repeated samples from a known distribution.
*   **Confidence Interval Construction**: Calculating confidence intervals for parameters (e.g., mean, proportion) from each simulated sample.
*   **Coverage Probability**: Calculating the proportion of simulated intervals that successfully contain the true parameter value and comparing it to the nominal (1 – α) level.
*   **Statistical Analysis**: Using R packages for data generation, interval estimation, and summarization of simulation results.

## How to Reproduce This Work
1.  Clone this repository to your local machine.
2.  Ensure you have R and RStudio installed.
3.  Open the `DSCI 3411 Project Code.Rmd` file in RStudio.
4.  Run the code chunks sequentially to execute the simulations and reproduce the results.
