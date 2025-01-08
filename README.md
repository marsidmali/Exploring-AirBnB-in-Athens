# 🏠 Exploring AirBnB in Athens

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An exploratory data analysis of Airbnb listings in Athens, Greece, using data from Inside Airbnb. This analysis investigates various aspects of the short-term rental market in Athens, including neighborhood distributions, pricing patterns, and host behaviors.

## ✨ Features

1. **Neighborhood Analysis**
   - Distribution of listings across neighborhoods
   - Interactive choropleth maps
   - Price statistics by neighborhood

2. **Temporal Analysis**
   - Daily availability patterns
   - Price variations over time
   - Seasonal trends identification

3. **Host & Property Analysis**
   - Distribution of listings per host
   - Room type analysis
   - Review patterns and occupancy rates

4. **Interactive Visualizations**
   - Interactive maps with listing details
   - Dynamic price trend plots

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/marsidmali/Exploring-AirBnB-in-Athens.git
cd Exploring-AirBnB-in-Athens
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `rogets_thesaurus_analysis.ipynb`
3. Run all cells to perform the analysis

## 📊 Data Source

The analysis uses data from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), specifically:
- Detailed listings data
- Calendar data
- Reviews data
- Neighborhood geojson data

## 🗺️ Interactive Map

The project includes an interactive map visualization (`map.html`) that shows:
- All Airbnb listings in Athens
- Cluster visualization for better performance
- Popup information for each listing including:
  - Listing name and URL
  - Host information
  - Availability and pricing
  - Property details

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
