

# Unemployment Analysis in India

This project aims to analyze unemployment trends in India using publicly available data. Various Python libraries are used to explore and visualize unemployment rates, labor participation, and employment trends across different regions and time periods.

## Dataset

The dataset used in this analysis is titled **Unemployment in India.csv**, which contains the following columns:

- `Region`: The region in India.
- `Date`: The time period of the data point.
- `Frequency`: Data collection frequency (e.g., monthly).
- `Estimated Unemployment Rate (%)`: The percentage of unemployed individuals.
- `Estimated Employed`: The number of employed individuals.
- `Estimated Labour Participation Rate (%)`: The percentage of the labor force participating in the economy.
- `Area`: Specifies if the region is rural or urban.

## Project Structure

1. **Data Loading and Inspection**:
    - The dataset is loaded using Pandas.
    - Basic inspection using `.info()`, `.head()`, and checking for missing values.
  
2. **Data Cleaning**:
    - Handles any missing or inconsistent data entries.
  
3. **Exploratory Data Analysis (EDA)**:
    - Visualizations using Matplotlib, Seaborn, and Plotly to understand unemployment trends.
    - Key metrics include unemployment rate, employment rate, and labor participation rate.

4. **Visualizations**:
    - Time series analysis of unemployment trends.
    - Regional comparisons of unemployment.
    - Correlations between labor participation and unemployment.

## Libraries Used

The following Python libraries are used in the project:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `datetime`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/saivamsi4514/JOB-ANALYSIS/
  
## Usage

1. Clone the repository.
2. Install the necessary dependencies using:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook to reproduce the analysis:
    ```bash
    jupyter notebook "unemployment analysis.ipynb"
    ```

## Conclusion

This analysis provides insights into how unemployment has evolved over time in India and highlights significant regional disparities. The visualizations help in identifying patterns in labor force participation and unemployment rates across urban and rural areas.

## Author
- CH.SAI VAMSI

##License
This project is licensed under the MIT License.
