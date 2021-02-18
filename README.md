# Measuring Systemic Risk with PCA - Absorption Ratio
## Objective:
Using Principal Component Analysis (PCA) to calculate Absorption Ratio as a measure of Systemic Risk.
## Background
Since the financial crisis in 2008 and the recent pandemic, governments and institutions have try to have better tools to meassure systemic risk and protect themselves against drastic shifts in the economy.

In 2010 few researches introduced the **absorption ratio** as an alternative to meassure implied systemic risk. The absorption ratio captures the extent to which markets are unified or tightly coupled. When markets are tightly coupled, they are more fragile in the sense that negative shocks propagate more quickly (Kritzman et al., 2010).

*Kritzman, Mark and Li, Yuanzhen and Page, Sebastien and Rigobon, Roberto, Principal Components as a Measure of Systemic Risk (March 31, 2010).* Available at SSRN: https://ssrn.com/abstract=1582687 or http://dx.doi.org/10.2139/ssrn.1582687

### Absorption Ratio equation:
![](/Images/A_ratioEq.PNG)

### PCA
PCA is a dimensionality- reduction method that is used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information from the original large set (Jaadi).

*Jaadi, Z. (n.d.). A step-by-step explanation of principal component analysis. Retrieved February 18, 2021, from https://builtin.com/data-science/step-step-explanation-principal-component-analysis

## Poject breakdown
- Get all the Stock tickers that compose the SP500 from Wikipedia
- Download historical time series files for each stock from Yahoo Finance
- Create a single dataframe with all the CSV files
- Use PCA to calculate the Absorption Ratio
- Visualisation and analysis
## Project's [Code](https://github.com/Oliver-vp/Jupyter_Notebooks/blob/main/PCA%20Absorption%20Ratio%20SP500.ipynb) Notebook
