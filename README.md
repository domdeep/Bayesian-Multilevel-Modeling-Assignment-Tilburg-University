# Bayesian Multilevel Models Group Project - Tilburg University

This repository contains all the final files from our submission for the **Bayesian Multilevel Models (880008-M-6)** course at Tilburg University, completed in **May 2024**. The project uses **Bayesian hierarchical models** for the analysis of clustered data using **R** and **brms**. This project received a grade of **8.5**.

## Project Overview

This group project involved applying **Bayesian multilevel models** to a dataset with clustered data. The goal was to model **sleep duration** based on various lifestyle and health factors, including stress levels, physical activity, and health conditions. The analysis involved fitting multiple models, performing **cross-validation**, and conducting **posterior predictive checks** to evaluate model performance.

## Objectives:
- **Dataset Analysis**: Selected a dataset with clusters and provided a detailed explanation of its structure and use.
- **Model Fitting**: Used the **brms R package** to fit multiple Bayesian models, including **log-normal** and **Gaussian models**.
- **Model Comparison**: Compared model performance using **k-fold cross-validation (CV)** and **Leave-One-Out Cross-Validation (LOO-CV)**.
- **Posterior Predictive Checks**: Performed posterior predictive checks to validate model accuracy and assess fit.
- **Parameter Interpretation**: Interpreted key model parameters, including estimates and credible intervals, and conducted **prior sensitivity analysis**.

## Algorithms Used:
- **Multilevel Lognormal Model**: Used to model sleep duration with a log-normal distribution.
- **Multilevel Gaussian Model**: Applied to continuous outcome data with Gaussian distribution.
- **Prior Sensitivity Analysis**: Explored the impact of various prior distributions on model outcomes.
- **Cross-Validation**: Employed both **k-fold CV** and **LOO-CV** for model comparison.

## Achievements:
- Successfully fitted and validated **Bayesian hierarchical models** to predict sleep duration based on health and lifestyle variables.
- **Best-Performing Model**: The multilevel Gaussian model demonstrated the best performance, outperforming other models based on the **expected log pointwise predictive density (ELPD)** and **WAIC**.
- Achieved the highest grade (**8.5**) in the course for model performance, interpretation of results, and comprehensive sensitivity analysis.

## Project Structure:
- **Code**: All R code is available in the form of **RMarkdown** files.
- **Report**: A detailed report, including model comparison, sensitivity analysis, and posterior predictive checks, is provided in **HTML** and **PDF** format.

## Group Members
- **Dominik Nguyen** (Model Fitting, Prior Sensitivity Analysis)
- **[Team Member 2 Name]** (Data Preprocessing, Cross-Validation)
- **[Team Member 3 Name]** (Posterior Predictive Checks, Model Comparison)
- **[Team Member 4 Name]** (Parameter Interpretation, Report Writing)
- **[Team Member 5 Name]** (Project Coordination, Final Report Compilation)

## Files Included
- **Bayesian_Multilevel.Rmd**: RMarkdown file containing the full code and analysis.
- **Bayesian_Multilevel_Report.pdf**: Final report in PDF format.
- **Bayesian_Multilevel_Report.html**: Final report in HTML format.
- **sleep_health_dataset.csv**: The dataset used for analysis.
