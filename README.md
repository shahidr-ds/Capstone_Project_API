# SpaceX Launch Data Analysis and Prediction Project

This repository contains the complete workflow and code used in the Coursera SpaceX Capstone Project. It includes data collection, processing, exploratory analysis, interactive dashboards, and predictive modeling.

## 📁 Project Structure

Each Jupyter Notebook corresponds to a distinct phase of the project:

### 1. [SpaceX\_API\_Calls.ipynb](./SpaceX_API_Calls.ipynb)

* Collected SpaceX launch data using REST APIs
* Parsed JSON responses and saved data to CSV

### 2. [Web\_Scraping.ipynb](./Web_Scraping.ipynb)

* Scraped additional SpaceX data from Wikipedia
* Merged scraped data with API-sourced dataset

### 3. [Data\_Wrangling.ipynb](./Data_Wrangling.ipynb)

* Cleaned and transformed datasets
* Handled missing values, unified formats, and ensured consistency

### 4. [EDA\_SQL.ipynb](./EDA_SQL.ipynb)

* Conducted SQL-based exploratory analysis
* Extracted insights on orbits, payloads, landing outcomes, etc.
### 5. EDA\_Pandas.ipynb

* Performs PANDAS-based exploratory data analysis
* Includes Visualisations 

### 6. [Folium\_Maps.ipynb](./Folium_Maps.ipynb)

* Built interactive maps using Folium
* Mapped launch sites and visualized outcomes with markers and color codes

### 7. [Plotly\_Dash.ipynb](./Plotly_Dash.ipynb)

* Developed interactive dashboards using Plotly Dash
* Included site-specific outcome summaries, scatter plots, and sliders

### 8. [Classification\_Model.ipynb](./Classification_Model.ipynb)

* Built and evaluated classification models
* Compared Logistic Regression, SVM, Decision Tree, and KNN
* Visualized accuracy and confusion matrix

## 🔧 Technologies Used

* Python, Pandas, NumPy
* REST API, BeautifulSoup (Web Scraping)
* SQL (via ipython-sql)
* Folium (Geospatial Visualization)
* Plotly Dash (Dashboard UI)
* scikit-learn (Classification Models)

## 🚀 Results Summary

* Mapped all SpaceX launch sites and outcomes on interactive Folium maps
* SQL and dashboard analysis highlighted payload and orbit success patterns
* **Decision Tree** model achieved the highest accuracy: **94.44%**

## 📂 How to Use

1. Clone this repository: `git clone https://github.com/shahidrasheed/Capstone-Project-SpaceX`
2. Open and run the Jupyter Notebooks in order of the project flow

## 🔗 Repository Link

**GitHub Repo:** [https://github.com/yourusername/spacex-project](https://github.com/shahidrasheed/Capstone-Project-SpaceX)

Each notebook is self-contained and ready for peer review.

Feel free to explore, fork, and contribute!
