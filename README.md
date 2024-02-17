# MA334-DATA-ANALYSIS-AND-STATISTICS-WITH-R

# Project Overview
# Objective

The code appears to be part of a data analysis project related to ecological species richness. The primary goal seems to be exploring and analyzing the relationship between ecological conditions, species richness, and various environmental factors.

# Libraries
Several R libraries are used in the project, including:

dplyr: For data manipulation and summarization.
ggplot2: For data visualization and plotting.
tidyr: For data tidying.
stringr: For string manipulation.
AICcmodavg: For model selection based on AICc.
gridExtra: For arranging multiple plots.
reshape2: For reshaping data.

# Data Loading and Preprocessing
The initial section involves setting the working directory, reading a CSV file (proportional_species_richness_V3.csv), and performing basic data preprocessing tasks. This includes converting some variables to factors and creating new variables like eco_status_7 representing the average ecological condition of seven selected species.

# Data Exploration
Correlation Heatmap
. The first exploration involves calculating the correlation between the seven selected species and creating a heatmap using ggplot2.

Mean Distribution Plots
. The second exploration includes two plots:

    . Mean distribution of the selected seven species for both periods.
    
    . Mean distribution of all eleven species for both periods.
    
. These visualizations provide insights into the distribution of ecological conditions.

# Extended Data Exploration
. This section involves additional explorations, including looking for correlations between continuous variables, analyzing geographical data, and conducting hypothesis testing.
# Hypothesis Testing

. Two hypothesis tests are performed.

   . The first test examines the difference in mean ecological scores between two periods for selected priority species.
   
   . The second test compares the difference in mean ecological scores between seven selected species and all eleven species for England.
   
# Linear Regression
Two linear regression models are fitted for the periods Y00 and Y70, exploring the relationship between eco_status_7 and ecologicalStatus. Diagnostic plots such as a correlation plot and QQ-plot for residuals are created.
# Multiple Linear Regression

. Two multiple linear regression models are built:

   . The first model includes all seven species.
   
   . The second model includes only species with p-values less than 2e-16.
   
. Predictions are made for test data, and correlation plots are generated.

# Open Analysis
The last section focuses on open analysis, examining and visualizing differences in mean species richness across locations and land zones in Wales, Scotland, and England. Visualizations include bar plots and facetted histograms.
# Conclusion
This project involves a comprehensive analysis of ecological species richness, including data preprocessing, exploration, hypothesis testing, linear regression, multiple linear regression, and open analysis. The code is well-commented and organized, making it understandable for others who may review or collaborate on the project.
