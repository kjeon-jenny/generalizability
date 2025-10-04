# Project Title: Generalizing study results: Feasible with the right variables; risky without

## Associated Publication
This repository contains the code and data necessary to reproduce the results presented in:

Kyungeun Jeon, M.S., Bryan Lau, Ph.D., Amii M. Kress, Ph.D., Elizabeth A. Stuart, Ph.D., "Generalizing study results: Feasible with the right variables; risky without," *[Journal Name]*, [Volume], [Issue], [Pages], [Year].

## Overview
This project provides a computational framework to illustrate when generalization from a nonrandom sample to the target population is valid and when it is not, including the implications of omitting variables that are and are not actual moderators. It includes scripts for data processing, model implementation, simulation execution, and result visualization.

## Repository Structure
To reproduce the simulation result, please follow these steps: 
1. Download the data file or create your own (population) data using the code in the Rmd file with seed(123).
2. Then run the functions in the Rmd file to get estimates. Function names are 'analysis.function.withem.same', 'analysis.function.withoutemx1.same', 'analysis.function.withoutem.same'.
3. Run the function called 'resultswrap.same' with the number of iterations you would like to.
4. Run the function called 'average.results' and you will get the averaged metrics of the iterated results.
5. Get the plots and tables with the functions 'create_plots.LR' or 'results.function.html'.
