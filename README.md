📊 Trends in Thunnus albacares Occurrence (GBIF Data)

🌊 Project Overview

This project explores temporal and spatial patterns in the occurrence records of Thunnus albacares — Yellowfin Tuna, using openly available biodiversity data from GBIF
.
The goal is to demonstrate how reproducible data workflows can uncover meaningful insights for marine conservation.

Main questions:

How have reported occurrences of Thunnus albacares changed over time?

Are there seasonal patterns in observations?

What are the potential implications for monitoring and conservation?


📂 Repository Structure
/data_download.ipynb   # Script to query & download raw occurrence data
/data_cleaning.ipynb   # Data cleaning & exploratory plots
/analysis.ipynb        # Statistical analysis & time series modeling
/map.html              # Interactive sampling map
/trend_dashboard.html  # Interactive trend visualization (Plotly)
/slides.pdf            # Summary slides for communication
/README.md             # Project documentation


🔧 Tech Stack

Language: Python 3.11 (or R alternative)

Libraries: pandas, numpy, matplotlib, seaborn, plotly, folium, statsmodels

Data Source: Global Biodiversity Information Facility (GBIF) API

Reproducibility: Jupyter Notebooks + GitHub


📊 Methods

Data Acquisition

Queried GBIF API for Thunnus albacares records between 2000 - 2024.

Exported data in CSV format.

Data Cleaning

Removed missing or invalid coordinates.

Converted and standardized event dates.

Extracted year and month fields.

Exploratory Analysis

Plotted annual occurrence counts.

Generated an interactive sampling map (Folium).

Statistical Analysis

Aggregated occurrences per month/year.

Conducted time series decomposition to identify trends and seasonality.

Applied linear regression to test for long-term change.

Visualization

Built interactive Plotly dashboard for temporal trends.

Created summary slides with key figures and conservation implications.


📈 Results (to fill in after analysis)

Trend: Occurrence records show [increase/decrease/stability] from [start year] to [end year].

Seasonality: Clear peaks observed in [months/season], suggesting [possible explanation].

Statistical test: Trend slope = [X], p = [Y] (significant / not significant).

🌍 Conservation Implications

These results suggest that:

[Species] sightings are [increasing/decreasing] in [region].

Seasonal occurrence patterns may align with [migration/spawning/fishing pressure].

Open biodiversity data can provide valuable signals for monitoring, though reporting biases should be considered.

📑 How to Reproduce

Clone the repo:

git clone https://github.com/[your-username]/coastal-species-trends.git
cd coastal-species-trends


Create environment & install requirements:

conda create -n marine-data python=3.11
conda activate marine-data
pip install -r requirements.txt


Run notebooks in order:

data_download.ipynb

data_cleaning.ipynb

analysis.ipynb


📬 Contact

Created by Felix Hinsch. 
Email: felixh8k@gmail.com
LinkedIn:
GitHub:

Feel free to connect with me on LinkedIn
or see more projects at GitHub.
