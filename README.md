# Project1
**Team Project #1:** Plotting Ideal Solar Farm Location in the San Francisco Bay Area

**Team Members:** Nurgul, Aaron, Tara

**Goal:** The goal of this project was to examine the three main factors that will influence the ROI and profitability of a solar farm: land price, hours of sunlight, and temperature.

We wanted to explore the variability in the San Franisco Bay Area for each of these three factors. To this end we looked at cities in all 9 Bay Counties, gathering relevant data.

1. Real estate - major factor the will determine the price of a solar installation
2. Sunlight hours - will determine how much power the solar farm can generate
3. Maximum temperature - this affects the efficiency of the solar farm. Higher temperatures reduce efficiency.

**Real Estate**
This data came from a Tabelau report from Redfin, looking at average real estate price per square foot within each city of interest.

**Sunlight Hours**
This data was pulled from one year of data from WorldWeatherOnline.

**Maximum Temperature Data**
This was pulled using an API call from the WorldWeatherOnline dataset for 1 year of past data.

## Code
The relevant code can be found in four numbered Jupyter Notebooks, ordered 1-4 in the order of the data collection and analysis process.
[1-Solar_Farms.ipynb](https://github.com/imtheaaron/Project1/blob/master/1-Solar_Farms.ipynb)
2-Citynameformatting.ipynb
3-API_weather_data.ipynb
4-Analysis_and_plotting.ipynb

## Results

**Real Estate Pricing Data:**
![Real Estate Pricing for 65 Bay County Cities](images/pricing.png)

**Sunlight Hours Data:**
![Sun Hours for 65 Bay County Cities](images/sun.png)

**Maximum Montly Temperatures:**
![Maximum monthly temps for 1 year from 65 Bay County cities](images/temp.png)

**Data Totals and Score for Best Location**
![Ideal location scores](images/normalized_plot.png)

**Results mapped onto Google Maps.**
Lighter colors are poorer locations, and darker colors are better locations for a solar farm considering price and the power a solar farm could generate
![solar locations mapped](images/locations_mapped.jpg)
