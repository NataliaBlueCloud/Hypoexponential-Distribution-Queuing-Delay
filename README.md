# Hypoexponential Distribution with 3 Links - Simulation and Analysis
This repository contains R Markdown code for simulating and analyzing a system with hypoexponential distribution across three links, as well as functions for calculating delays for a variable number of links (N). The simulation is conducted using the _simmer_ package, and theoretical calculations are performed using _igraph_ and _EnvStats_.

## Hypoexponential Distribution: 
In the context of multiple parallel M/M/1 links, the service time distribution is not necessarily exponential anymore. Instead, it follows a hypoexponential distribution, which is a mixture of exponential distributions.

## Properties of Hypoexponential Distribution:
- Mean and Variance: The mean and variance of a hypoexponential distribution can be calculated based on the parameters of the exponential components in the mixture.
- Probability Density Function (PDF): The PDF of a hypoexponential distribution is a weighted sum of the PDFs of its exponential components.

## Usage
### Input Data
Specify the system parameters such as capacity of the links in Gbps (**Capacity_Gbps**), load for each link, and the packet size (**N**).

## Igraph Theoretical Calculations
This section uses the igraph package to perform theoretical calculations and visualize the network graph.

## Simulation and Delay Comparison
The code calculates both theoretical and simulated delays for the three links to compare the results.

# n-Number of Links Functions and Calculation example
This section contains functions for calculating the theoretical and simulated delays for a system with a variable number of links (**n**).

# Installation and Setup
Before running the code, ensure that you have the required R packages installed:

- **igraph**
- **simmer**
- **dplyr**

You can install these packages using the install.packages() function in R.
```R
install.packages(c("igraph", "simmer", "dplyr"))
```

# Results
The results of the simulation and analysis are presented in the code output and visualizations generated by the R code.
