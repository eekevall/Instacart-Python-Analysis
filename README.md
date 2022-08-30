# Instacart-Python-Analysis
A python analysis of the Instacart database for the CareerFoundry Data Analysis course using Jupyter Notebook.

## Project Overview
Instacart, an online grocery store that operates through an app is considering a targeted marketing strategy. The stakeholders want to know more information about their sales patterns, especially the variety of customers in their database along with their purchasing behaviours.

They have requested an initial exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.

To address this objective and the key questions below the Instacart data sets were imported into Jupiter Notebook and analysed using Python.

### Key Questions
* What are the busiest days of the week and hours of the day?
* Are there particular times of the day when people spend the most money?
* Can the data be clustered into simpler price range groupings to help direct their efforts?
* Are there certain types of products that are more popular than others? 
* What’s the distribution among users in regards to their brand loyalty?
* Are there differences in ordering habits based on a customer’s loyalty status?
* Are there differences in ordering habits based on a customer’s region?
* Is there a connection between age and family status in terms of ordering habits?
* What different classifications does the demographic information suggest? 
* What differences can you find in ordering habits of different customer profiles?

### Data Analysis Tasks

* Data cleaning, wrangling and consistency checks
* Consider data ethics when dealing with customer information
* Merge all data sets into a dingle data set (over 32M records)
* Conduct exploratory data analysis
* Derive new variables and create flags (grouping and aggregating the data ) to help with the analysis
* Create visualizations communicating insights for stakeholders

### Tools
The full analysis was carried out using the following **Python libraries** in Jupyter Notebook:
   * pandas | numpy | os | matplotlib pyplot | seaborn | scipy | plotly express

The results were then exported or copied into Excel.

### Data
The Instacart project brief and datasets were provided by Career Foundry: 
Instacart Project Brief: PDF file
* Instacart_Project_Brief.pdf

The original datasets (in the compressed folder - 02_Data/02_1_Original_Data) were provided as csv files.
* Customers, Orders_products_prior, Orders, Products,
* Departments (used to create a data dictionary which was mapped to the dataframe)

#### The Instacart Population Flow Diagram

The grey boxes in the first row represent the four original datasets that were eventually merged into the final dataset Orders_products_all.<br>
The second row of coloured boxes represent the datasets after the cleaning process.<br>
The final row represents the datasets after each of the merges.<br>

