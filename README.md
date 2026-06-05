# weather-patterns-viz
Analysis and visualization of ERA5 weather data using Python, Xarray, and NetCDF to explore atmospheric patterns and meteorological variables.

# Weather Patterns Visualization

Analysis and visualization of ERA5 weather data using Python, Xarray, and NetCDF.

## Project Overview

This project explores meteorological and atmospheric variables from ERA5 reanalysis datasets. The notebook demonstrates data loading, preprocessing, spatial analysis, and visualization techniques commonly used in weather and climate studies.

The analysis focuses on understanding weather patterns through variables such as temperature, pressure, humidity, and wind components.

## Dataset

The project uses ERA5 reanalysis data, a global atmospheric dataset produced by the European Centre for Medium-Range Weather Forecasts (ECMWF).

### Variables Analyzed

* Temperature
* Surface pressure
* Relative humidity
* Wind speed and direction
* Other atmospheric variables available in the dataset

## Technologies Used

* Python
* NumPy
* Pandas
* Xarray
* NetCDF4
* Matplotlib

## Project Structure

```text
weather-patterns-viz/
├── Notebook/
│   └──Weather_Analysis.ipynb
├── requirements.txt
└── README.md
```

## Analysis Workflow

1. Load ERA5 weather data from NetCDF files.
2. Explore dataset dimensions and metadata.
3. Extract meteorological variables of interest.
4. Perform exploratory data analysis.
5. Interpret observations from the generated plots.



## Installation

Clone the repository:

```bash
git clone https://github.com/cathciyal/weather-patterns-viz.git
cd weather-patterns-viz
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/ERA5_Weather_Analysis.ipynb
```

and execute the cells sequentially.

## Future Improvements

* Interactive weather visualizations
* Additional atmospheric variables
* Time-series forecasting experiments
* Comparative analysis across locations

## Author

Aruna Cathciyal Gilbert Radjou

M.Sc. Data Science, Hochschule Fulda
