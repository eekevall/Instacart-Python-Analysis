# Instacart-Python-Analysis
A python analysis of the Instacart database for the Career Foundry Data Analysis course using Jupyter Notebook.

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
* Merge all datasets into a single dataset (over 32M records)
* Conduct exploratory data analysis
* Derive new variables and create flags (grouping and aggregating the data) to help with the analysis
* Create visualizations communicating insights for stakeholders

### Tools
The full analysis was carried out using the following **Python libraries** in Jupyter Notebook:
   * pandas | numpy | os | matplotlib pyplot | seaborn | scipy | plotly express

The results were then exported or copied into Excel.

### Data
The Instacart project brief and original datasets were provided by Career Foundry.

Instacart Project Brief: PDF file
* [Instacart_Project_Brief.pdf](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/01_Project_Management/Instacart_Analysis_Project_Brief.pdf)

The following csv files are in folder 02_Data/02_1_Original_Data
* [Customers](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/02_Data/02_1_Original_Data/customers.csv), [Products](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/02_Data/02_1_Original_Data/products.csv), [Departments](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/02_Data/02_1_Original_Data/departments.csv) (used to create a data dictionary which was mapped to the dataframe)

And the two larger csv files can be downloaded
* [Orders_products_prior](https://drive.google.com/file/d/1Phw5ijub5khXtwYU7zCBvFmanmDiutIX/view?usp=sharing), [Orders](https://drive.google.com/file/d/1fiFWyVlIW1iQNeF5yrkA9ULI9cXT6jfW/view?usp=sharing) 

## Project Findings

#### The Instacart Population Flow Diagram
![Instacart Population Flow Diagram](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/Instacart_Population_Flow.png)
The grey boxes in the first row represent the four original datasets that were eventually merged into the final dataset Orders_products_all.<br>
The second row of coloured boxes represent the datasets after the cleaning process.<br>
The final row represents the datasets after each of the merges.<br>

### Report and Datasets Sent to Client
Instcart Analysis Final Report: Excel file 
* [Instcart_Analysis_Final_Report.xlsx](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/05_Sent_to_Client/Instcart_Analysis_Final_Report.xlsx)

Also available in pdf format
* [Instcart_Analysis_Final_Report.pdf](https://github.com/eekevall/Instacart-Python-Analysis/blob/main/05_Sent_to_Client/Instcart_Analysis_Final_Report.pdf)

The two client data files - Analysis_all_customers and Analysis_active_customers - that would have been in folder 05_Sent_to_Client, but are to large (1.94GB) can been downloaded along with the interactive treemap visualisations:
* Link to [client data files](https://drive.google.com/drive/folders/1GanmHISFNL-XtfQ2-6IQ3ZAKD1-Ts3_i?usp=sharing) and [interactive treemaps](https://drive.google.com/drive/folders/1Tg2-X1Od2aE1nNZ2QEthgkvkAk4wfeJI?usp=sharing)

