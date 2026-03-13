# A Nonparametric Approach to Inference and Forecasting in the Italian Electricity Spot Market

This repository contains a statistical and inferential analysis of the Italian electricity market trends, focusing on Zonal Price data recorded in 2023 and 2024.

## Abstract
In highly volatile markets such as the electricity sector, understanding structural dynamics is crucial for strategic planning and informed decision-making. This study focuses on the Italian electricity market, specifically on the Day-Ahead Market, where supply and demand offers are matched to determine hourly zonal prices. Unlike traditional time series approaches, we adopt a functional data analysis framework, treating entire supply and demand curves as single data objects. This allows for a more detailed understanding of market behavior. The first part of the study identifies recurrent patterns in the price evolution, revealing a characteristic double-peak structure within each day. These peaks are largely driven by demand surges, which shift the market equilibrium upward. Conversely, lower prices during weekends are explained by significant drops in demand, despite a generally increased production level. As a short-term prediction model, we implement a FAR(1), which leverages temporal correlations among the curves. Despite its simplicity and the absence of structural constraints, the model successfully captures the essential features of the data, proving preferable to more rigid semi-parametric alternatives in terms of predictive curve realism. Furthermore, conformal prediction intervals at 90\% confidence are constructed using a modulated $L^\infty$ non-conformity measure, accounting for local variability. While effective in many regions, these bands remain wide near areas of sharp functional jumps. Overall, this structural, curve-based approach offers both descriptive insight and predictive power.

## WARNING
> **IMPORTANT:** The folders `DatasetXML` and `DatasetCSV` are not present in this repository due to privacy policy.

## Repository Structure
* **results/**: Contains the generated plots including zonal trends, nonparametric analysis, and hourly/daily groupings.
* **docs/**: Full documentation (Final_Report.pdf) of results, methodology, and statistical conclusions.
* **scripts/**: R source code used for data processing, curve reconstruction, and functional time series modeling.

## License and Usage Policy

This project follows a dual-licensing approach:

### 1. Code (MIT License)
The source code and scripts in this repository are licensed under the **MIT License**. You are free to use, modify, and distribute the code, provided that the original copyright notice is included.

### 2. Report and Visual Results
All other files, including the scientific report text and the images in the `results` folder, are subject to the following terms:

* **Academic & Personal Use**: You are free to use, copy, and distribute these files for non-commercial purposes, provided that appropriate credit is given to the original authors (Arianna Cagali, Mattia Gastoldi, Roberto Gastoldi).
* **Commercial Use**: Reproduction or use of the contents (report, findings, or posters) for profit is **strictly prohibited** without explicit written consent.
* **Disclaimer**: The data and analyses are provided "as is." The authors assume no responsibility for financial or operational decisions made based on the findings of this study.

