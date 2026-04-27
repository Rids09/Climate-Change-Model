# Climate Change Analysis: CO₂ and Temperature Trends

A comprehensive data analysis project exploring the relationship between atmospheric CO₂ concentrations and global temperature changes using historical climate data.

## Overview

This project analyzes climate data spanning multiple decades to understand patterns in CO₂ emissions and temperature variations across different geographical scales. The analysis includes data visualization, correlation studies, and predictive modeling to forecast future CO₂ levels.


## Key Features

### Data Processing
- Data cleaning and NaN value removal
- Date format standardization and year extraction
- Dataset merging for cross-analysis
- Aggregation of temperature and CO₂ data by year

### Visualizations
- Scatter plots showing temperature trends above and below 9°C
- Linear regression plots for CO₂ concentration trends
- Correlation heatmaps for multiple datasets
- Interactive Plotly visualizations showing:
  - Average CO₂ levels per year
  - Seasonal fluctuations in CO₂ levels
  - Rolling and exponentially weighted moving averages
  - Predicted vs. actual CO₂ concentrations

### Analysis Highlights
- **United States Temperature Trends**: Focused analysis on U.S. state temperature data
- **Correlation Studies**: Relationship between temperature and CO₂ levels
- **Extreme Values**: Identification of highest recorded temperatures by location
- **Predictive Modeling**: Linear regression model for CO₂ concentration forecasting

## Key Findings

- **Highest Average Temperature (State)**: Delhi, India - 36.339°C (June 2012)
- **Highest Average Temperature (Country)**: Kuwait - 38.842°C (July 2012)
- **Model Accuracy**: Linear regression model achieves 99.6% accuracy in predicting CO₂ levels

## Technologies Used

- **Python 3.11.6
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Static visualizations
- **seaborn**: Statistical data visualization
- **plotly**: Interactive charts and graphs
- **scikit-learn**: Machine learning and predictive modeling

## Installation

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
```

## Usage

1. Ensure all CSV files are in the correct directory structure:
   ```
   ./data/archive.csv
   ./data/ClimateChange/GlobalLandTemperaturesByCity.csv
   ./data/ClimateChange/TemperaturesByCountry.csv
   ./data/ClimateChange/TemperaturesByMajorCity.csv
   ./data/ClimateChange/TemperaturesByState.csv
   ./data/ClimateChange/GlobalTemperatures.csv
   ```

2. Run the Jupyter notebook or Python script

3. Interactive plots will be generated using Plotly

## Predictive Model

The project implements a linear regression model that:
- Uses year, month, and their squared values as features
- Achieves 99.6% prediction accuracy
- Forecasts CO₂ concentrations from 1950 to 2055
- Includes both rolling averages and exponentially weighted moving averages

## Data Insights

### Temperature Analysis
- Analysis focuses on U.S. state temperatures with 9°C as a threshold
- Identifies regions with extreme temperatures
- Tracks temperature uncertainty across different time periods

### CO₂ Trends
- Clear upward trend in atmospheric CO₂ concentrations
- Seasonal fluctuations captured and visualized
- Strong correlation between time and CO₂ levels

## Future Enhancements

- Incorporate additional climate variables (humidity, precipitation)
- Expand predictive models with deep learning approaches
- Add geographical mapping visualizations
- Include climate policy impact analysis
- Real-time data integration capabilities

## Data Sources

The datasets contain historical climate records from various monitoring stations and research institutions worldwide, spanning from the 18th century to recent years.

## License

Please refer to the original data sources for licensing information.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for improvements.

## Acknowledgments

Special thanks to the climate research community for making these valuable datasets available for analysis.
