# COVID-19 Global Data Tracker

## Project Description

This project analyzes and visualizes global COVID-19 data focusing on cases, deaths, recoveries, and vaccination progress. It demonstrates data cleaning, exploratory data analysis (EDA), advanced visualizations including interactive choropleth maps, and reporting insights—all using Python.

The goal is to provide an insightful, easy-to-understand dashboard/report suitable for presentation or publication.

---

## Project Objectives

- Import and clean real-world COVID-19 data from reliable sources  
- Perform detailed time series analysis of cases, deaths, and vaccinations  
- Compare COVID-19 metrics across selected countries (e.g., Kenya, USA, India)  
- Create clear, insightful visualizations including line charts, rolling averages, and heatmaps  
- Build interactive choropleth maps for geographic visualization of pandemic impact  
- Summarize key insights, anomalies, and trends with narrative reporting  

---

## Tools and Libraries Used

- Python 3.x  
- Jupyter Notebook / Google Colab  
- pandas — data loading and manipulation  
- matplotlib & seaborn — static data visualizations  
- plotly — interactive choropleth maps and enhanced plotting  
- scipy — signal processing for peak detection in time series  
- Google Drive integration (for persistent file storage in Colab)  

---

## How to Run / View the Project

1. **Download Dataset:**  
   Download `owid-covid-data.csv` from [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data).

2. **Upload Dataset:**  
   - Upload manually to your working directory if running locally, or  
   - Upload to Google Drive and mount Drive in Colab for persistent access.

3. **Install Dependencies:**  
   If running locally or in Colab, install required packages with:  
   ```bash
   pip install pandas matplotlib seaborn plotly scipy
