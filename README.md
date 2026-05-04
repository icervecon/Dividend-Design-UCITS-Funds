REPLICATION FILES

This repository contains the data and code required to replicate the empirical results presented in:

"Dividend Policies as Product Design: Evidence from UCITS Funds"

ABSTRACT

This paper examines the factors associated with dividend policies in UCITS funds, focusing on investor targeting, regulatory classification, and economic accessibility. Using a comprehensive dataset, we document a strong and robust relationship between retail investor targeting and the likelihood of distributing dividends. This relationship persists within management groups, indicating that retail targeting reflects product-level design choices.

In contrast, regulatory classifications and economic accessibility, proxied by minimum investment requirements, do not exhibit robust explanatory power once controls and firm-level heterogeneity are taken into account. We further show that the interaction between retail targeting and asset class is driven by differences across asset management firms and disappears when controlling for management group fixed effects.

Overall, the results indicate that dividend policies reflect both product design and firm-level strategies, and that failing to distinguish between within- and across-firm variation may lead to misleading interpretations of product-level effects.

FILES

-ucits_dividend_data.xlsx
Dataset containing all transformed variables used in the empirical analysis.

-Paper_Dividend_Design_UCITS.ipynb
Jupyter Notebook with the code required to reproduce the results.

DATA AVAILABILITY AND REPLICABILITY

The original data are sourced from LSEG and are subject to proprietary restrictions. Due to licensing agreements, the raw data cannot be made publicly available.

The dataset provided in this repository contains all transformed variables necessary to replicate the empirical analysis.

REPLICATION INSTRUCTIONS

Download all files in the repository.
Open analysis.ipynb in a Python environment (e.g., Jupyter Notebook or JupyterLab).
Install the required Python packages if not already available.
Run the notebook sequentially to reproduce the results.

COMPUTATIONAL ENVIRONMENT

The analysis is conducted in Python. The main packages used include:
-pandas
-numpy
-statsmodels

REMARKS

The replication files are intended solely for academic and research purposes.
All variable constructions correspond to those used in the paper.
