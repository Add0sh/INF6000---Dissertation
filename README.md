NBA Defensive Metrics Analysis (2010–2024)

This repository contains R scripts for analyzing NBA team-level defensive metrics across regular seasons and playoffs (2010–2024).
The project explores how team defense translates to playoff performance, using statistical modeling, visualization, and predictive analysis.

FEATURES:

Data Summarisation - 
Aggregates steals, blocks, defensive rebounds, turnovers, FG%, and plus-minus per team and season. 
Compares regular season vs playoff metrics.

Visualisations -
Bar charts & heatmaps showing team-specific differences.
Line graphs tracking defensive performance over time.
Scatter plots comparing regular vs playoff performance.

Statistical Testing - 
Shapiro-Wilk normality tests for defensive metric differences.
Paired t-tests and Wilcoxon tests to assess significance.
MANOVA models for multivariate differences between regular season and playoffs.

Predictive Modeling - 
Linear regression models linking regular-season defensive stats to playoff performance.
Multiple Linear Regression (MLR) with multicollinearity & homoscedasticity checks.
Lasso regression for variable selection.
ARIMA time-series forecasting of team metrics.

Team-Specific Analysis
Focused case studies for: Miami Heat, Boston Celtics, Indiana Pacers, Oklahoma City Thunder, San Antonio Spurs & Portland Trail Blazers.

Requirements - This project is written in R and requires the following packages:
library(tidyverse)
library(dplyr)
library(ggplot2)
library(patchwork)
library(readr)
library(plotly)
library(shiny)
library(randomForest)
library(ggpmisc)
library(ggrepel)
library(ggpubr)
library(forecast)
library(car)
library(lmtest)
library(glmnet)
