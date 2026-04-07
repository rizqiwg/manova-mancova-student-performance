# MANOVA & MANCOVA Analysis on Student Performance

## Overview

This project implements Multivariate Analysis of Variance (MANOVA) and Multivariate Analysis of Covariance (MANCOVA) to analyze factors affecting student academic performance.

The study focuses on:

* School support (schoolsup)
* Higher education intention (higher)
* Study time (studytime) as a covariate

## Dataset

Dataset used:

* Student Performance Dataset (UCI Machine Learning Repository)

## Objectives

* Analyze the effect of school support on student performance
* Analyze the effect of motivation (higher education intention)
* Evaluate interaction effects between variables
* Assess the role of study time as a covariate

## Methods

The following statistical methods were applied:

* MANOVA (Multivariate Analysis of Variance)
* MANCOVA (Multivariate Analysis of Covariance)
* ANOVA & ANCOVA (Univariate follow-up tests)
* Post-Hoc Tukey Test

## Key Findings

* School support and higher education intention significantly affect academic performance (multivariate)
* Study time plays a significant role in multivariate analysis
* Motivation (higher) is the most consistent factor affecting final scores
* No significant interaction effect between variables

## Assumptions

* Multivariate normality: not fully satisfied
* Homogeneity: partially satisfied
* Pillai’s Trace used for robustness

## Tools

* R
* R Markdown
* Statistical packages: MVN, car, biotools, tidyverse

## Report

This repository includes:

* R Markdown file (.Rmd)
* HTML output

## Author

* Lintang Isa Mardani, Ivan Cahya Aryasuta, Rizqi Wahyu Gusniadi

## Reference

UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/320/student+performance
