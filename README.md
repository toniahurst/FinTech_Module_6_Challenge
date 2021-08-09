# FinTech_Module_6_Challenge

## Description

In this challenge, we used a variety of visualization tools to analyze the San Francisco rental housing market as a member of Proptech, a app for the real estate market. Proptech is conducting a trial run of its one-click service for people to buy and sell real estate. If the trial is successful in the San Francisco market, the service would be expanded to other markets. Our job (using geospatial tools, aggregation, and visualizations) is to identify potential properties to investors.

Fig. 1: sale_price_sqr_foot, housing_units, and gross_rent in San Francisco 2010 - 2016

![Fig. 1](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%201.png)

Fig. 2: San Francisco Housing Units by Year 2010 - 016

![Fig. 2](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%202.png)

Fig. 3: San Francisco Housing Units Sorted by Year 2010 - 2016

![Fig. 3](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%203.png)


Fig. 4: Prices by Year and Neighborhood 2010 - 2016

![Fig. 4](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%204.png)


Fig. 5: San Francisco Housing Units by Neighborhood 2010 - 2016

![Fig. 5](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%205.png)


Fig. 6: San Francisco Sale Price Square Foot by Gross Rent 2010 - 016

![Fig. 6](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%206.png)


Fig. 7: San Francisco Neighborhoods Ranked by Gross Rent 2010 - 2016

![Fig. 7](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%207.png)


Fig. 8: San Francisco Neighborhoods Ranked by Sale Price Square Foot 2010 - 2016

![Fig. 8](https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/Fig.%208.png)

Compose Your Data Story
Based on the visualizations that you have created, compose a data story that synthesizes your analysis by answering the following questions:

Question How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?

Answer # From 2010 to 2016, both Gross Rent (gross_rent) and Sale Price Per Square Foot (sale_price_sqr_foot) rose at a steady rate, though the rate of increase was much higher for Gross Rent than for Sale Price Per Square foot suggesting a overall robust market for rental properties. However, on closer examination it is clear that additional attention should be paid to specific neighborhoods before any decision is made. The ideal locations for the company's business model would be the properties which have a decreasing sale price sqr foot and increasing gross rent.

Question What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

Answer # While gross rents across the city are uniformly outpacing the sale price sqr foot, the best locations to invest (based on the factors evaluated) are those neighborhoods which have high gross rent and lower or declining sale price sqr foot. The results of this analysis indicate that more detail is needed to make a good recommendation. Though there are many areas which have high gross rents and some that also have low or static sale price per square foot, without taking into consideration costs (such as repairs, insurance, taxes, and vacancy days) and other aspects such as square footage, it is difficult to say which properties are best.

Based on the data, the properties I would consider further are: Westwood Park, Bayview Heights, Visitacion Valley, Merced Heights, Inner Parkside, Outer Mission, North Beach, Van Ness/Civic Cneter, Financial District South, and Oceanview.

## Technologies

This program uses Python 3.7.10, Pandas, Anaconda version 4.10.3, and JupyterLab 3.0.14. It also uses libraries from pandas, JSON, Dotenv, OS, Plotly Express, and Pathlib. It was written on macOS Catalina 10.15.7. It uses the Mapbox API public key.

## Usage

Open the Jupyter Lab notebook at https://github.com/toniahurst/FinTech_Module_6_Challenge/blob/main/FinTech_Module_6_Challenge_Starter_Code/san_francisco_housing.ipynb or download the notebook and run from the CLI.

## Contributors

Antonia Hurst

## License
Copyright (c) 2015-2021 Project Jupyter https://github.com/jupyterlab/jupyterlab/blob/master/LICENSE
