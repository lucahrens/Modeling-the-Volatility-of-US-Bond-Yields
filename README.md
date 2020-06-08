# Modeling-the-Volatility-of-US-Bond-Yields
After completeing a GARCH analysis in R course through Data Camp I took on this project (provided by Data Camp https://www.datacamp.com/projects/738) to apply my newly learned skills. The desciption of the project, the text in the notebook, and the outline of the code is provided by Data Camp.
In this project, we will explore the volatility structure of US Government Bond Yields. Essentially all financial assets exhibit a phenomenon called volatility clustering where low and high volatility regimes follow each other. The alternating volatility regimes are a focus for risk management and investment decisions. We will use the well-known GARCH (Generalized AutoRegressive Conditional Heteroskedasticity) method to explore the statistical properties of financial time series data.  This project assumes background knowledge on time series analysis, GARCH modeling, plotting and uses packages xts and rugarch. You can get familiar with GARCH modeling if you check out the course GARCH Models in R.  The historical yield data are published by the US Federal Reserve Data Releases and imported from Quandl, https://www.quandl.com/data/FED/SVENY,
