# COVID-19 Data Analysis and Visualization

This project provides an in-depth analysis and interactive visualization of various COVID-19 datasets. The goal is to explore the data to understand the pandemic's impact across different regions and demographics, and to identify trends and patterns in the data. The visualizations are created using Plotly Express, allowing for interactive exploration of the data. ☣️

---

## 📊 Datasets

This project utilizes three distinct datasets to provide a comprehensive analysis of the COVID-19 pandemic:

* **`covid.csv`**: This dataset offers a global overview of the pandemic, containing key metrics for each country. It includes columns such as `Country/Region`, `Continent`, `Population`, `TotalCases`, `TotalDeaths`, `TotalRecovered`, `ActiveCases`, `TotalTests`, and `WHO Region`.
* **`covid_grouped.csv`**: This file presents a time-series perspective of the pandemic, with data grouped by date and country. It tracks the daily progression of `Confirmed`, `Deaths`, `Recovered`, and `Active` cases, as well as new daily cases.
* **`coviddeath.csv`**: This dataset focuses on COVID-19 deaths in the United States, providing a detailed breakdown by pre-existing conditions, age groups, and states. It helps in understanding the comorbidities and risk factors associated with COVID-19 mortality. The columns in this dataset include: `Data as of`, `Start Week`, `End Week`, `State`, `Condition Group`, `Condition`, `ICD10_codes`, `Age Group`, `Number of COVID-19 Deaths`, and `Flag`.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/Mahesh77300/Covid_19_Data_Analysis_And_Visualization.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Covid_19_Data_Analysis_And_Visualization
    ```
3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

---

## 📈 Visualizations

The analysis in this project is presented through a variety of interactive visualizations, including:

* **Bar Charts**: To compare key metrics like total cases, deaths, and tests across different countries and continents.
* **Scatter Plots**: To explore the relationships between different variables, such as total cases versus total deaths, and total tests versus total cases.
* **Bubble Charts**: To visualize continent-wise data, where the size of the bubbles represents the magnitude of cases or deaths.
* **Choropleth Maps**: To illustrate the geographical distribution of confirmed cases across the globe over time.
* **Word Clouds**: To highlight the countries most frequently mentioned in the dataset.

---

## 🛠️ Technologies Used

* **Python**: The core programming language used for the analysis.
* **Pandas**: For data manipulation and cleaning.
* **Plotly Express**: For creating interactive and insightful visualizations.
* **Matplotlib**: For generating static plots.
* **WordCloud**: For creating word cloud visualizations.
* **Jupyter Notebook**: For interactive development and presentation of the analysis.