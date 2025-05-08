# Dublin Air Pollution Analysis Report

This repository contains the analysis and findings from a report commissioned by Dublin City Council to investigate the key factors contributing to air pollution in Dublin and to support the development of actionable strategies for improving air quality.

## Project Overview

The report analyzes the "DCC Google-AirView" dataset, which includes over 5 million data points of second-by-second measurements for various pollutants: Carbon Monoxide (CO), Carbon Dioxide ($CO_{2}$), Nitrogen Dioxide ($NO_{2}$), Nitric Oxide (NO), Ozone ($O_{3}$), and Particulate Matter (PM2.5), including particle counts from 0.3-2.5 µm. The data were collected along typical urban routes in Dublin during weekday working hours (9:00-17:00) in 2025.

The analysis assessed the structure and completeness of the data using summary statistics and missingness proportions. While PM2.5 data had the lowest proportion of missing values, the report highlights the limitations posed by missing data for other pollutants, particularly $NO_{2}$, in assessing traffic-related impacts.

## Key Findings

* PM2.5 levels in Dublin appear to be more strongly influenced by meteorological conditions than by traffic volume.
* The absence of consistent $NO_{2}$ measurements limited the ability to thoroughly assess traffic-related air pollution.

## Recommendations

The report proposes the following recommendations for Dublin City Council:

1.  **Install Fixed-Site Monitoring Stations:** Establish continuous, multi-pollutant (PM2.5, $NO_{2}$, $O_{3}$, $CO_{2}$) monitoring stations in high-pollution areas to enable more accurate forecasting, multi-pollutant modeling, and targeted interventions. The example of London's ULEZ, which pairs traffic regulation with continuous monitoring, is provided.

2.  **Implement a Forecast-Based Air Quality Alert System:** Develop a Random Forest-based, forecast-driven alert system for high-pollution periods and locations, particularly focusing on PM2.5. This system should inform the public, especially vulnerable groups, via mobile apps or text messages with clear behavioral guidance (e.g., limiting outdoor activity, mask use). South Korea's national real-time forecast system is cited as an example.

## Repository Contents

* **Report.pdf:** The full Dublin Air Pollution Analysis Report.
* **Notebook Code.ipynb:** [Likely contains the Python code used for data analysis and generating the findings of the report - *Note: This is based on the filename provided*].

## Usage

To understand the analysis in detail, please refer to the **Report.pdf** file. If you wish to examine the code used for the analysis, please open and run the **Notebook Code.ipynb** file (requires a Jupyter Notebook environment and necessary Python libraries).

## Contributing

[Optional: Add information about how others can contribute to this project, e.g., reporting issues, suggesting improvements.]

## License

[Optional: Include the license under which this project is released.]

## Authors

* DANIEL HENECK
* DARRAGH MCGEE
* KOFI BARTON-BYFIELD

## Acknowledgements

Commissioned by Dublin City Council.