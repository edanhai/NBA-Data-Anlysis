# NBA Data Analysis and Scraping

## Project Overview

This project involves analyzing NBA player data and scraping NBA statistics from online sources. The work is divided into two major components:

1. **Data Analysis**: A detailed examination and visualization of NBA player data to derive insights.
2. **Web Scraping**: Collecting NBA statistics programmatically from external data sources.

---

## Key Components

### 1. **Data Analysis**
- **Libraries Used**: `pandas`, `plotly`
- **Data Source**: `nba_player_data.xlsx`
- **Steps Included**:
  - Data sampling and exploration
  - Cleaning data by dropping unnecessary columns (`RANK`, `EFF`)
  - Visualizing player statistics using interactive charts

### 2. **Web Scraping**
- **Libraries Used**: `pandas`, `requests`, `time`, `numpy`
- **Scraping Target**: NBA statistics from the [NBA Stats API](https://stats.nba.com/)
- **Steps Included**:
  - Sending GET requests to fetch data in JSON format
  - Parsing and storing data from the `resultSet`
  - Demonstrating response handling for API queries

---

## Insights
- The analysis highlights the importance of clean, structured data for visualizations.
- Scraping NBA statistics ensures up-to-date and dynamic datasets for analysis.
