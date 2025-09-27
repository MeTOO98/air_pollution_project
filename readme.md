-----

### ⚙️ Data Engineering & Data Analysis Project: The Environmental Impact of Car and Factory Emissions — and Potential Solutions.

This project showcases a complete data pipeline, from raw data ingestion and transformation (data engineering) to advanced visualization and insight generation (data analysis). The goal is to analyze the environmental impact of urban factors like car populations and industrial activity.

-----

### 🛠️ Data Engineering Pipeline

The **data engineering** phase focuses on building a robust pipeline to clean, integrate, and prepare the raw data for analysis. The process is handled primarily within the `FinalProject.ipynb` Jupyter Notebook.

1.  **Data Extraction**: The project starts by extracting data from three separate `.csv` files:

      * `Number-of-cars-and-factories.csv` (Primary data on vehicle and factory counts)
      * `Trees-and-Filters.csv` (Data on tree cover and factory filters)
      * `new_countries.csv` (Supplementary geographic data for context)

2.  **Data Transformation**: The extracted data is transformed using the **Pandas** library. This involves:

      * Cleaning and standardizing data formats.
      * Merging the three datasets into a single, comprehensive DataFrame based on shared keys like `Country` and `City`.
      * Handling any missing values or inconsistencies to ensure data integrity.

3.  **Data Loading**: The final, cleaned dataset is prepared and loaded for use in the data analysis phase. The output is a clean, structured dataset that can be easily consumed by business intelligence tools.

-----

### 📊 Data Analysis & Visualization

Following the data engineering pipeline, the **data analysis** phase uses the prepared data to uncover meaningful insights and trends. This is primarily done using **Power BI**, which leverages the clean dataset to create an an interactive and dynamic dashboard.

The analysis addresses key questions:

  * **Correlation Analysis**: Exploring the relationship between car populations (both diesel and gasoline) and pollutant levels
  * **Impact Assessment**: Investigating how the presence of industrial filters and Trees correlates with pollutant levels.
  * **Geographical Comparison**: Benchmarking countries and cities against each other based on their combined environmental and industrial data.

The insights from this analysis are presented in a live dashboard, accessible here: [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGYzZTcyZjMtYjM2Zi00ZjY3LTllNGMtZmJkN2E0M2JjZGQ1IiwidCI6ImM5NDdhYWExLTUxYzUtNDY3Yi04YWUwLTFhYTY0NzUxNmJjZiJ9)

-----

### 📂 Repository Contents

  * `FinalProject.ipynb`: Jupyter Notebook for the data engineering and initial analysis.
  * `finalproject.pbix`: Power BI project file with the complete dashboard.
  * `Number-of-cars-and-factories.csv`: Raw dataset 1.
  * `Trees-and-Filters.csv`: Raw dataset 2.
  * `new_countries.csv`: Raw dataset 3.
  * `FinalProject_1.drawio.png`: Data WareHouse Schema.

-----

### 🚀 Getting Started

1.  Clone this repository.
    ```bash
    git clone [your-repo-link]
    ```
2.  Run the cells in `FinalProject.ipynb` to execute the data engineering pipeline and generate the cleaned data.
3.  Open `finalproject.pbix` with Power BI Desktop or visit the live dashboard link to explore the visualizations.

-----

### 💻 Technologies Used

  * **Python**: For data manipulation and scripting.
  * **Pandas**: A key library for data engineering tasks.
  * **Jupyter Notebook**: For creating the reproducible data pipeline.
  * **Power BI**: For data visualization and dashboard creation.

-----
