### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#descriptions)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgments](#licensing)

## Installation<a name="installation"></a>

The Jupyter Notebooks present in this repository were created using Python 3 (any Python 3.* should work)

Furthermore, for **Data Processing**, the following packages were used:

- Pandas and Geopandas
- Numpy

For **Visualization**:

- Matplotlib
- Seaborn
- Geoplot

## Project Motivation<a name="motivation"></a>

Apart from the controverse impacts on housing markets, a landlord's main goal will often be to maxamize revenue made from the space they own.
Leaving legal concernce aside, this project intents to estimate the average revenue one can expect from hosting a space on Airbnb and compare it to the average rent.

To keep things simple, the following framework / assumptions were made:
-**Revenue will be compared on district basis**
-**

1. **What's the average price per (grouped) neighborhood in Berlin?**
2. **What's the occupancy rate of active airbnb listings in Berlin?**
3. **What's the average revenue of active airbnb listings in Berlin?**
4. **How does this compare to the average revenue from normal rent in those distircts?**
5. **How does Superhost status effect listing's revenue?**

## File Descriptions<a name="descriptions"></a>

There are two different Jupyter Notebooks in this repository. They are both explicitly named for people to understand what they do. 

- **Airbnb - Data Processing and Imputation**: Preprocessing of the boston airbnb data for 2017 is computed. Anything ranging from data gathering and assessing to cleaning and imputing missing values. 

- **Airbnb - Data Analysis**: Analysis of the previous preprocessed data is done and many visualizations are computed to help answer the questions in the motivation. This notebook contains some light processing, modelling, visualising and detailed explanations and conclusions about the data,

## Results<a name="results"></a>

The main conclusions and results can be found in the notebook *Airbnb - Data Analysis*. But if you wish for a cleaner and better written results you can check my blog post on Medium [here](https://medium.com/@miguel.a.r.diass/start-hosting-in-boston-like-a-boss-d8c9849b163e).

## Licensing, Authors, and Acknowledgments<a name="licensing"></a>

Shoutout to Airbnb for providing a great dataset for analysis. The licensing for this dataset is available [here](https://www.kaggle.com/airbnb/boston). Thank you for your interest in my analysis and feel free to use my code for anything you'd like. 

Cheers.
