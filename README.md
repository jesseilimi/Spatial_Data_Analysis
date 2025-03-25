# Space Time Exploration of Metro-Police Crime Data (April 2021 - March 2024)

## Introduction

### Project Overview

The objective of this project is to conduct a comprehensive space-time exploration of crime data and crime types from April 2021 to March 2024, obtained from the metropolitan police. By analyzing the temporal and spatial patterns of crime, we aim to uncover insights that can inform law enforcement strategies and policy decisions. This project will utilize various statistical and data visualization techniques to identify trends, hotspots, and correlations in the crime data.

### Importance of the Study

Understanding the dynamics of crime over time and space is crucial for effective crime prevention and resource allocation. By identifying temporal trends and spatial hotspots, law enforcement agencies can deploy resources more efficiently and develop targeted interventions. This study will provide valuable insights into the patterns of criminal activities, helping to improve public safety and reduce crime rates.

## Data Description

The dataset provided by the metropolitan police includes detailed records of crime incidents from April 2021 to March 2024. Each record contains multiple fields, which are described below:

### Data Fields

1. **Crime ID**: A unique identifier for each crime incident.
   - **Count**: 702,265
   - **Description**: Each crime incident has a unique Crime ID to distinguish it from others.

2. **Month**: The month when the crime occurred.
   - **Count**: 702,265 (no missing values)
   - **Description**: The month is recorded to track the temporal pattern of crime incidents.

3. **Reported by**: The organization that reported the crime.
   - **Count**: 702,265 (no missing values)
   - **Description**: Indicates the reporting authority for the crime incident.

4. **Falls within**: The jurisdiction under which the crime falls.
   - **Count**: 702,265 (no missing values)
   - **Description**: Specifies the jurisdiction or geographical boundary.

5. **Longitude**: The longitude coordinate where the crime occurred.
   - **Count**: 702,265 (no missing values)
   - **Description**: Used for spatial analysis of crime locations.

6. **Latitude**: The latitude coordinate where the crime occurred.
   - **Count**: 702,265 (no missing values)
   - **Description**: Used for spatial analysis of crime locations.

7. **Location**: A textual description of the crime location.
   - **Count**: 702,265 (no missing values)
   - **Description**: Provides additional context about the crime location.

8. **LSOA code**: The Lower Layer Super Output Area code where the crime occurred.
   - **Count**: 702,265 (no missing values)
   - **Description**: Used for demographic and geographical analysis.

9. **LSOA name**: The name corresponding to the LSOA code.
   - **Count**: 702,265 (no missing values)
   - **Description**: Provides a readable name for the LSOA code.

10. **Crime type**: The category of the crime.
    - **Count**: 702,265 (no missing values)
    - **Description**: Categorizes the nature of the crime (e.g., burglary, robbery).

11. **Last outcome category**: The outcome of the crime investigation.
    - **Count**: 702,265 (no missing values)
    - **Description**: Indicates the final status or resolution of the crime.

12. **Context**: Any additional context or information about the crime.
    - **Count**: 702,265 (no missing values)
    - **Description**: Provides supplementary details.

## Project Structure

### Notebooks

- **Data Cleaning and Preprocessing.ipynb**: Notebook for cleaning and preparing the data for analysis.
- **Exploratory Data Analysis.ipynb**: Notebook containing various EDA techniques to understand the data.
- **Spatial Analysis.ipynb**: Notebook focusing on the spatial patterns and hotspots of crime incidents.
- **Temporal Analysis.ipynb**: Notebook focusing on the temporal trends and patterns in the crime data.
- **Visualization.ipynb**: Notebook containing various visualizations to represent the findings.

### Data

- **crime_data.csv**: The main dataset containing crime records from April 2021 to March 2024.

### Output

- **Reports**: Generated reports and findings from the analysis.
- **Visualizations**: Plots and maps generated from the data.

## Installation

To run the notebooks and reproduce the analysis, you need to have Python installed along with the following packages:

- pandas
- numpy
- matplotlib
- seaborn
- geopandas
- folium
- jupyter

You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn geopandas folium jupyter
```

## Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the desired notebook and run the cells to perform the analysis.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Reporting issues
- Forking the repository and making changes
- Submitting pull requests

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

I would like to thank the metropolitan police for providing the crime data used in this analysis.


 
