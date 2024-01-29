# **About Geotechnical Engineering Research Projects**

Welcome to the directory of `Geotechnical-Research`. This directory, part of `My-Data-Science-Projects`,
contains my research projects in Geotechnical Engineering which incorporate machine learning algorithms.
I will usually build the underlying mathematical frameworks of the computations or the frameworks describing the
directions of the research.

## **Current Projects**

### 1. [ML-Driven Solution to the Lateral Pile Capacity for Long Piles in Geotechnical Engineering](/Geotechnical-Research/ML_Driven_Solution_of_long_pile.ipynb)

This research focuses on an innovative method for estimating lateral pile capacity in geotechnical engineering,
building upon the theoretical groundwork laid by ([Broms, 1964a](https://doi.org/10.1061/JSFEAQ.0000611) and
[Broms, 1964b](https://doi.org/10.1061/JSFEAQ.0000614)) and further generalized by
[(Cecconi et. al, 2019)](https://doi.org/10.1016/j.sandf.2019.01.007). Traditionally, estimating the lateral pile
capacity of long piles involves solving higher-degree polynomials, a method deemed impractical. In response,
we propose a numeric solution by employing a machine learning (ML) model trained on data generated from corresponding
polynomial equations to estimate the lateral pile capacity. The theoretical framework of the ML model is presented,
along with key performance evaluation parameters. Our results demonstrate that the ML model achieves considerable
accuracy, offering a time-effective alternative to the conventional method of solving higher-degree polynomials.

### 2. [A Numeric Optimization on a Semi-Analytic Model of Soil Swelling Potential](/Geotechnical-Research/Soil_Swelling_Potential.ipynb)

We have conducted a laboratory test to investigate the soil swelling potential. A cylindrical soil sample is subjected
to constant loading. The deformation of the sample is recorded over time. The data is then processed such that we obtain
the soil strain over time. In this notebook, we will build a mathematical model to describe the strain as a function
of time by incorporating a semi-analytic approach. That is, we employed statistical analysis on the laboratory dataset
to confirm an inherited mathematical property from the dataset which leads to a differential equation (DE) model.
We provided a solution to the DE model, and then further optimized the solution using a numeric optimization technique.
All computations are conducted in this notebook. The original paper manuscript can be accessed
[here](http://dx.doi.org/10.13140/RG.2.2.21197.61928). In the original paper, we also showed that a pure analyitic
optimization to the solution of the DE model is not possible, hence the importance of the numeric optimization.
