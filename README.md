# Project3-Communicate-Data-Findings

This project has been done as part of Data Anaylst Nanodegree Program from Udacity. 

## Project Overview

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

In Part I, Exploratory data visualization, we will use Python visualization libraries to systematically explore a selected dataset, starting from plots 
of single variables and building up to plots of multiple variables.
In Part II, Explanatory data visualization, we will produce a short presentation that illustrates interesting properties, trends, and relationships
that you discovered in your selected dataset. The primary method ofconveying your findings will be through transforming your exploratory visualizations
from the first part into polished, explanatory visualizations.

## Dataset: 
This project conducts an exploratory and explanatory data analysis on the Ford GoBike System Dataset. The dataset, provided by Udacity, includes information
about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the month of February 2019. This analysis aims to uncover
insights into the usage patterns of the bike-sharing system and to understand the characteristics of the trips taken by members.

## Preliminary Wrangling

The analysis begins with loading the dataset, performing initial observations, and then proceeds to clean and prepare the data for exploration. Key steps 
in the data wrangling process include:

- Loading the data from `'201902-fordgobike-tripdata.csv'`.
- Inspecting the dataset for cleanliness, and structure, and performing any necessary cleaning operations.
- Investigating the dataset for null values and outliers and addressing them accordingly.

## Key Findings

Initial exploration focuses on understanding the structure of the dataset, which consists of 183,412 trips with 16 features. The key features of interest 
include trip duration, start and end times, user type (subscriber or customer), and others. The dataset was cleaned to remove outliers and fill in missing 
values, setting a solid foundation for further analysis.

## Installation

To run this project, following libraries are needed:

- NumPy
- pandas
- Matplotlib
- seaborn

Ensure you have Python 3 installed, and then you can install the dependencies with:

pip install numpy pandas matplotlib seaborn

Usage
To explore the dataset:

Clone the repository to your local machine:
git clone https://github.com/N-R07/Project3-Communicate-Data-Findings/
Navigate to the project directory:
cd Project3-Communicate-Data-Findings
Start Jupyter Notebook:
bash
Copy code
jupyter notebook
Open the notebook file Part_I_ford_bike_dataset.ipynb to view the analysis.
Contributing
Contributions to improve the analysis or explore new facets of the dataset are welcome. Please follow these steps to contribute:

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

## License
This project is licensed under Udacity Honor Code.

## Acknowledgments
Udacity for providing the Ford GoBike System Dataset.
The Ford GoBike System for making their data publicly available for educational purposes.
