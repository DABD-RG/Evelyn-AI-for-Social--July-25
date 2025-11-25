# Analyzing the Trend and Correlation between Crime Rates and School Dropouts in India Using Power BI  


## Project Overview
The project analyzes the relationship between crime rates and school dropout rates across various states in India. The project uses statistical methods to identify potential correlations and presents the data through interactive visualizations.


## Key Analyses Performed
The core of this project is a statistical correlation analysis to investigate the following relationships:
*   The correlation between school dropout rates and juvenile crime rates.
*   The relationship between female literacy rates and the incidence of crimes against women.
*   The connection between school dropout rates and the rates of child marriage and child trafficking.


## Methodology
The project began with collecting crime and school dropout data from official government sources. The datasets were cleaned and standardized to ensure consistency before being imported into Power BI for visualization. Interactive dashboards were created to highlight trends and disparities, and correlation analysis using Pearson and Spearman methods was applied in Jupyter Notebook to measure relationships between dropout rates and crime levels.

## Repository Structure

*   `Datasets/`: Contains all the data used in this project.
    *   `Source Dataset/`: The primary raw dataset (`Data.csv`).
    *   `Power BI Datasets/`: Processed and unpivoted Excel files that have been structured for optimal use within the Power BI dashboard.

*   `Power BI Visualisation/`: Contains the `Crime & Dropout Rates.pbix` file, which is the interactive dashboard used for visualizing data.
  
*   `Correlation Analysis/`: Includes the statistical analysis components.
    *   `Correlation Analysis Code.ipynb`: A Jupyter Notebook with the Python code used to perform the statistical correlation analyses.
    *   `Datasets for Correlation Analysis/`: CSV files used for the correlation analysis.

*   `Article/`: A directory for the article.

## Usage Instructions

### Data Visualization
The interactive dashboard can be accessed by opening the `Power BI Visualisation/Crime & Dropout Rates.pbix` file in Microsoft Power BI Desktop.  
During setup, upload the `Data.csv` file from the `Datasets/Source Dataset/` directory to ensure the underlying data is properly loaded for visualization.

### Statistical Analysis
The correlation analysis is implemented in the `Correlation Analysis/Correlation Analysis Code.ipynb` Jupyter Notebook.  
Execution requires Python with the `pandas` and `scipy` libraries installed.  
The CSV files contained in the `correlation_analysis/datasets/` folder must be located in the same directory as the notebook.

