# Visualizing Inequalities in Life Expectancy
## Description 
Do women live longer than men? How long? Does it happen everywhere? Is life expectancy increasing? Everywhere? Which is the country with the lowest life expectancy? Which is the one with the highest? In this project, we will answer all these questions by manipulating and visualizing United Nations life expectancy data using `ggplot2`.

The dataset can be found [here](http://data.un.org/Data.aspx?d=GenderStat&f=inID:37&c=1,2,3,4,5,6&s=crEngName:asc,sgvEngName:asc,timeEngName:desc&v=1) and contains the average life expectancies of men and women by country (in years). It covers four periods: 1985-1990, 1990-1995, 1995-2000, and 2000-2005.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analysis.
## Contents
1. **United Nations life expectancy data:** Load libraries and the dataset.
2. **Life expectancy of men vs. women by country:** Manipulate the dataset to contain male and female life expectancy for each country.
3. **Visualize I:** Create a basic scatter plot for male vs. female life expectancy.
4. **Reference lines I:** Add reference lines and axis limits.
5. **Plot titles and axis labels:**
6. **Highlighting remarkable countries I:**
7. **How has life expectancy by gender evolved?:**
8. **Visualize II:**
9. **Reference lines II:**
10. **Highlighting remarkable countries II:**