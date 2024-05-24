# Phonepe-Pulse-Data-Visualization-and-Exploration-A-User-Friendly-Tool-Using-Streamlit-and-Plotly

This is an open-source project repo which deals with extracting data from PhonePe Pulse dataset available in [github](https://github.com/PhonePe/pulse/tree/master), cleaning, transforming and loading it into MySQL database. Data visualization and exploration are done using Streamlit and Plotly charts or graphs. 

##**Introduction**:
  PhonePe, India's leading fintech platform, launched PhonePe Pulse, India's first interactive website with data, insights and trends on digital payments in the country. The PhonePe Pulse showcases more than 2000+ Crore transactions by consumers on an interactive map of India. This project aims at Extracting, Transforming and Loading data from [source repository](https://github.com/PhonePe/pulse/tree/master) into MySQL and visualizing, exploring the data by creating a Streamlit application along with Plotly charts. 
Note : This project works on the data timelined between **2018 and 2023**.

## Table of Contents

1. Pre-requisites
2. Technology Stacks
3. Usage
4. Data Extraction
5. Data Cleaning and Transformation
6. Migrating to MySQL
7. Visualization and Exploration
8. Further Improveents


## Pre-requisites

Install the following packages to run the project. 

pip install streamlit
pip install pandas
pip install os
pip install json
pip install mysql.connector
pip install plotly
pip install requests
pip install plotly
pip install pillow
pip install sqlalchemy

## Technology Stack
* Python scripting
* SQL- MySQL
* Streamlit App development
* Github Data Extraction
* Plotly

## Usage

Clone the repo from the below mentioned link. 
[PhonePe-Data-Visualization-and-Exploration](https://github.com/Chindhu-Alagappan/PhonePe-Data-Visualization-and-Exploration) 
Install packages from "requirement.txt"
Run the streamlit application using 'streamlit run .\PhonePe.py'
View the portal in your [localhost](http://localhost:8501/)

## Data Extraction

Clone the PhonePe Pulse data from the source repo and save it to your local. 

Extract the following data as dataframe from the source directory.















