# Guvi-HCL-Project-1
Project 1 Review 1

AQI Mapping and Dashboard Project
Author: Arpan Chatterjee
Internship: GUVI + HCL Summer Industry Internship
Repo URL: https://github.com/ArpanC03/GuviProject1DataScience

📌 Project Overview
This project visualizes and analyzes Air Quality Index (AQI) data for Indian cities using Python, Google Colab, Power BI, and Streamlit.
Interactive dashboards and charts help users explore trends, rank cities by air quality, and investigate spatial patterns.

🚀 Features
Scrollable, filterable city-state AQI table

Dynamic KPIs: Total cities, average AQI, most/least polluted cities

Interactive India map: color-coded AQI markers (Plotly/Power BI)

Distribution/box plots, city ranking bar charts, pie charts

Reproducible notebooks and dashboards: run everything from data cleaning to report generation

Colab + Power BI + Streamlit web dashboard (demo included)


📁 Project Structure

|-- india_aqi.csv             # AQI dataset
|-- Project1_GUVI_DataScience.pdf # Project report/slides
|-- HCL+GUVI_Project-1.ipynb  # Python/Colab notebook - data prep & EDA
|-- app.py                    # Streamlit dashboard app
|-- <dashboard>.pbix          # Power BI dashboard file (if downloadable/exported)
|-- README.md                 # (this file)


⚙️ Requirements
Python 3.x

Google Colab or Jupyter Notebook (recommended for notebook)

Packages: pandas, matplotlib, seaborn, plotly, folium, xmltodict, missingno, streamlit

Power BI Desktop (for .pbix dashboard, optional)

Streamlit (for web dashboard, optional)

Chrome/Edge/Firefox (for dashboard viewing)

Install required Python libraries:

bash
  pip install pandas plotly matplotlib seaborn folium xmltodict missingno streamlit


🔧 Project Setup
1. Data Preparation and EDA (Colab Notebook)
Open HCL+GUVI_Project-1.ipynb in Colab or Jupyter Notebook.

Run through all cells:

Imports, data upload, cleaning, summarization.

Generates summary outputs, various charts, mapping, and saves figures.

Outputs: PNG images, HTML folium maps, processed dataset.

2. Power BI Dashboard
Open the .pbix file in Power BI Desktop.

If opening from scratch:

Import india_aqi.csv

Create map, charts, tables, and slicers as shown in the PDF/ppt.

(Export PDF/screenshots as needed for your report).

3. Streamlit Dashboard
Place app.py and india_aqi.csv in the same directory.

Launch app locally:

bash
  streamlit run app.py
  
For sharing via Colab & localtunnel:

Install Node.js and localtunnel, then run:

bash
  !streamlit run app.py & npx localtunnel --port 8501
  
Open the printed URL in your browser.


🛠️ Reproducibility
All code and files are provided. To reproduce:

Download this repo.

Run the notebook for all Python/Colab analysis and plots.

Open Power BI dashboard file in Power BI Desktop.

Run the dashboard app via Streamlit for a web-based experience.

Data cleaning and logic are in the notebook; dashboards refresh directly from india_aqi.csv.


📊 Demo & Outputs
See the document section or .PDF file (or PPT in repo) for visuals and main dashboard screenshots.

Run the Streamlit app or Power BI file for full interactive experience.


📬 Contact
Name: Arpan Chatterjee

Roll: 2312RES162, IITP

Email: arpan2312res162@iitp.ac.in

GitHub:[ [Your GitHub profile link here]](https://github.com/ArpanC03)


