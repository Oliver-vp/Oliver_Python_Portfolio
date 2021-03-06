# Measuring Systemic Risk with PCA - Absorption Ratio
## Objective:
Applying Principal Component Analysis (PCA) to the  group of stocks that conform the S&P500 in order to calculate the Absorption Ratio as a measure of Systemic Risk.
## Background
Since the financial crisis in 2008 and the recent pandemic, governments and institutions have try to create better tools to meassure systemic risk and protect themselves against drastic shifts in the economy.

In 2010 few researches introduced the **absorption ratio** as an alternative to meassure implied systemic risk. The absorption ratio captures the extent to which markets are unified or tightly coupled. When markets are tightly coupled, they are more fragile in the sense that **negative shocks** propagate more quickly (Kritzman et al., 2010).

*Kritzman, Mark and Li, Yuanzhen and Page, Sebastien and Rigobon, Roberto, Principal Components as a Measure of Systemic Risk (March 31, 2010).* Available at SSRN: <https://ssrn.com/abstract=1582687> or <http://dx.doi.org/10.2139/ssrn.1582687>.

### Absorption Ratio equation:

![](/Images/A_ratioEq1.PNG)

### PCA
PCA is a dimensionality- reduction method that is used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information from the original large set (Jaadi).

*Jaadi, Z. (n.d.). A step-by-step explanation of principal component analysis. Retrieved February 18, 2021, from <https://builtin.com/data-science/step-step-explanation-principal-component-analysis>

## Poject breakdown
In this section it will be explained the calculation of the Absorption Ratio in Python and a visualisation of the ratio against the S&P500 along with an analysis. After that, some specific periods will be broken down for a more granular analysis. At the end of this section there is a general description of the code's steps and a link to the code in a Jupyter Notebook.
- Get all the Stock tickers that compose the S&P500 from Wikipedia
- Download historical time series CSV files for each stock from Yahoo Finance
- Create a single dataframe with all the CSV files
- Use PCA to calculate the Absorption Ratio
- Visualisation and analysis
## Project's [Code](https://github.com/Oliver-vp/Jupyter_Notebooks/blob/main/PCA%20Absorption%20Ratio%20SP500.ipynb) Notebook
