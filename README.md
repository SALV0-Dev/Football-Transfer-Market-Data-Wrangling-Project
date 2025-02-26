# Transfer Market Data Wrangling

## Overview
I created this project to perform data wrangling and data analysis on football (soccer) transfer market data, specifically for the 2022/2023 Premier League season. My main aim is to clean, transform, and analyze the data to gain powerful insights into market trends, player valuations, and club performances.

## Dataset
I use CSV files containing transfer market data:
- `clubs.csv` - Club details, including market values and squad information.
- `players.csv` - Player profiles and attributes.
- `player_valuations.csv` - Historical player valuation data.
- `competitions.csv` - Information on different competitions.
- `games.csv` - Match details.
- `appearances.csv` - Player appearances in matches.

## Features
- **Data Acquisition**: I read multiple CSV files into pandas DataFrames.
- **Data Cleaning**: I drop unnecessary columns, handle missing values, and standardize data formats.
- **Data Transformation**: I merge relevant datasets, process dates, and calculate key statistics.
- **Visualization**: I use Matplotlib to generate insights from the data.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/transfer-market-dw.git
   cd transfer-market-dw
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```sh
   jupyter notebook DW_project_code_v121321.ipynb
   ```

