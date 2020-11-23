### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#descriptions)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgments](#licensing)

## Installation<a name="installation"></a>

The Jupyter Notebooks present in this repository were created using Python 3 (any Python 3.* should work)

The following packages were used:

- Pandas and Geopandas
- Numpy
- Matplotlib
- Seaborn

## Project Motivation<a name="motivation"></a>

Apart from the controverse impacts on housing markets, a landlord's main goal will often be to maximize revenue made from the space they own.
Leaving legal concernce aside, this project intents to estimate the average revenue one can expect from hosting a space on Airbnb and compare it to the average rent.

To keep things simple, the following framework is set:
-**Revenue will be compared on neighborhood basis and for entire homes/apartments**
-**Occupancy will be estimated using reviews and minimum days a customer has to stay**

Qustions to answer:
1. **What's the average price per (grouped) neighborhood in Berlin?**
2. **What's the occupancy rate of airbnb listings in Berlin?**
3. **What's the average revenue of airbnb listings in Berlin?**
4. **Does being a Superhost effect the average revenue?**
5. **How does this compare to the average revenue from normal rent in those neighbourhoods?**

## File Descriptions<a name="descriptions"></a>

There are 2 notebooks available here related to answering the above questions. 
The data preparation notebook focuses on preparing the data for analysis, which in turn is kept in the data analysis notebook.
Markdown cells were used to assist in walking through the thought process for individual steps.

## Results<a name="results"></a>

The main conclusions and results can be found in the *Data Analysis* notebook. 
But if you wish for a cleaner and better written results you can check my blog post on Medium [here](https://medium.com/@felix.kinzius/airbnb-or-long-term-lease-in-berlin-5d78d828a69f).

## Licensing, Authors, and Acknowledgments<a name="licensing"></a>

Shout-out to http://insideairbnb.com/ for providing a great dataset for this analysis under a Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license. 

Thank you for your interest in my analysis and feel free to use my code for anything you'd like. 

Stay curious!