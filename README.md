# **IBM Applied Data Science Capstone \- Final Project**

This repository contains the files for the Final Project of the **IBM Applied Data Science Capstone** course on Coursera, also known as *The Battle of the Neighborhoods*.

## **Project Description**

This project aims to analyze and segment the neighborhoods of a selected city using Machine Learning (K-Means Clustering). The results provide data-driven recommendations for stakeholders, such as identifying the optimal locations to open a new business (e.g., restaurants, coffee shops) based on the proximity to popular venues.

## **Data Used**

1. **Geospatial/Neighborhood Data:** Dataset containing borough names, postal codes, and the latitude and longitude coordinates of the analyzed city.  
2. **Foursquare API:** Used to retrieve location data (venues) around specific neighborhoods, including venue categories, popularity, and specific geographic locations.

## **Methodology**

* **Data Collection:** Web scraping and utilizing the RESTful API (Foursquare).  
* **Data Cleaning:** Handling missing values and formatting datasets using pandas.  
* **Exploratory Data Analysis (EDA):** Basic statistical analysis and data visualization.  
* **Machine Learning:** Implementing the **K-Means Clustering** algorithm from scikit-learn to group neighborhoods with similar venue characteristics.  
* **Geospatial Visualization:** Mapping the clustered results using the Folium library.

## **Directory Contents**

Within the Final Project folder, you will find the main components of the project:

1. **Jupyter Notebook (.ipynb):** Contains all Python code for data gathering, preprocessing, K-Means modeling, and map visualization.  
2. **Project Report (PDF):** A comprehensive document detailing the introduction, business problem, data description, methodology, results, discussion, and conclusion.  
3. **Project Presentation (PDF/PPT):** A summary slide deck of the project report aimed at stakeholders.

## **Python Libraries Used**

* pandas & numpy for data manipulation.  
* requests & BeautifulSoup for web scraping and API calls.  
* scikit-learn for machine learning (K-Means).  
* matplotlib & seaborn for data visualization.  
* folium for interactive map rendering.