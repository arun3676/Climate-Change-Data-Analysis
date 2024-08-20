# Climate Change Data Analysis Project

## Overview
This project analyzes climate change trends using global temperature anomalies, CO2 emissions, and sea level data. The analysis aims to quantify changes over time and explore relationships between these climate indicators.

## Data Sources
- Global temperature anomalies: [NASA GISS Surface Temperature Analysis](https://data.giss.nasa.gov/gistemp/)
- CO2 emissions: [Our World in Data CO2 Emissions](https://github.com/owid/co2-data)
- Sea level data: [NOAA Global Sea Level Trend](https://www.star.nesdis.noaa.gov/socd/lsa/SeaLevelRise/)

## Project Structure
1. `data_collection.py`: Scripts for downloading and initial processing of data
2. `data_cleaning.py`: Data cleaning and preprocessing functions
3. `analysis.py`: Main analysis scripts, including trend calculations and correlations
4. `visualization.py`: (Note: Limited due to matplotlib issues) Basic data visualization functions
5. `main.py`: Runs the entire analysis pipeline

## Key Findings
- Temperature Trend: 0.018°C/year
- CO2 Emissions Trend: 312.5 million tonnes/year
- Sea Level Trend: 3.4 mm/year

## Tools Used
- Python 3.9
- Pandas 1.3.3 for data manipulation
- NumPy 1.21.2 for numerical computations
- Matplotlib 3.4.3 and Seaborn 0.11.2 (limited use due to technical issues)

## How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run `python main.py`

## Future Work
- Incorporate regional data for more granular analysis
- Implement advanced statistical methods (e.g., time series forecasting)
- Develop interactive visualizations

## Contributors
Arun Kumar Chukkala

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- NASA GISS for temperature data
- Our World in Data for CO2 emissions data
- NOAA for sea level data
