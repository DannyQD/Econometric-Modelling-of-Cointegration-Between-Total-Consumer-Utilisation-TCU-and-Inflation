Econometric-Modelling-of-Cointegration-Between-Total-Consumer-Utilisation-TCU-and-Inflation

📌 Overview

This project performs a comprehensive time series analysis of **Inflation**, represented by the **Consumer Price Index (CPI)**, and **Capacity Utilisation**, represented by the **Total Consumer Utilization (TCU)** rate. The analysis employs various econometric techniques to investigate the dynamic relationship between these two critical economic indicators. 

Objectives
- To assess whether inflation and capacity utilisation are stationary over time.
- To explore the long-run and short-run relationships between inflation and capacity utilisation using cointegration techniques.
- To model the interdependencies between the two-time series through Vector Autoregression (VAR) and Vector Error Correction Models (VEC).
- To analyse the causal relationships and the effects of shocks through Granger causality tests and impulse response functions.

Prerequisites
1. **Install R**: Ensure you have R installed on your machine. You can download it from [CRAN](https://cran.r-project.org/).
2. **Install RStudio** (optional): RStudio is a great IDE for R. You can download it from [RStudio](https://www.rstudio.com/products/rstudio/download/).

Required R Packages

This project requires the following R packages:

- dynamac
- forecast
- tseries
- nlme
- pdfetch
- zoo
- urca
- vars
- car
- dynlm
- tsDyn
- gets
- readxl
- aod
- egcm
- aTSA
- tidyverse
- lattice
- gridExtra

Installation Instructions

To install the required packages, run the following command in R:

```R
install.packages(c("dynamac", "forecast", "tseries", "nlme", "pdfetch", "zoo", "urca", 
                   "vars", "car", "dynlm", "tsDyn", "gets", "readxl", "aod", 
                   "egcm", "aTSA", "tidyverse", "lattice", "gridExtra"))
