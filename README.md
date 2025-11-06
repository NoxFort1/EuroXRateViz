# Euro Exchange Rates: Presidential Analysis
Data storytelling project analyzing EUR-USD exchange rates (1999-2021) across Bush, Obama, and Trump presidencies.

## Overview
Visual analysis of 22 years of daily Euro-Dollar exchange rates using FiveThirtyEight styling. The project creates a three-panel visualization showing how the exchange rates evolved during three US presidential terms.

**Key Findings**: Average EUR-USD rate of **1.22** across all three presidencies, ranging from 0.94 to 1.44.

## Technologies
* Python 3.11
* Pandas, Matplotlib, NumPy
* Jupyter Notebook

## Installation
```
git clone https://github.com/NoxFort1/EuroXRateViz.git
cd EuroXRateViz
pip install pandas matplotlib numpy
jupyter notebook Storytelling_Data_Visualization_on_Exchange_Rates.ipynb
```
## Dataset
* **Source**: [European Central Bank](https://www.kaggle.com/datasets/lsind18/euro-exchange-daily-rates-19992020)
* **Period**: January 4, 1999 - December 31, 2020
* **Frequency**: Daily update
* **Curator**: Daria Chemkeava

## Results
| **Perios** | **President** | **Start Rate** | **End Rate** |
| :--------- | :------------ | :------------- | :----------- |
| 2001-2009  | Bush          | 0.9423         | 1.4406       |
| 2009-2017  | Obama         | 1.4406         | 1.0541       |
| 2017-2021  | Trump         | 1.0541         | 1.2250       |

## Visualization
Three-panel plot with color-coded presidential periods:
* **Purple** (Bush) - Euro strengthening phase
* **Orange** (Obama) - Post-crisis adjustment
* **Blue** (Trump) - Moderate recovery

## Licence
MIT Licence

## Author
[@NoxFort1](https://github.com/NoxFort1)
