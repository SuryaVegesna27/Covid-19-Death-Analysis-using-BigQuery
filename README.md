### README

## COVID-19 Deaths in USA

### Description
This project provides statistics on deaths involving COVID-19, pneumonia, and influenza reported to the National Center for Health Statistics (NCHS) by sex, age group, and jurisdiction of occurrence. Using datasets from the CDC and US Census, the analysis aims to identify the most vulnerable groups and provide insights for targeted interventions.

### Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.7** or higher installed
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **requests**, **Google Cloud SDK** libraries installed

### Datasets
1. **Provisional COVID-19 Deaths by Sex and Age:**
   URL: [CDC Data](https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku)
2. **Total Population State-wise of USA:**
   URL: [US Census Data](https://www.census.gov/data/datasets.html)

### Installation and Setup
To install and set up the project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/covid19-deaths-usa.git
   cd covid19-deaths-usa
   ```

2. **Set up the Python Environment:**
   Create a virtual environment and install the required libraries:
   ```sh
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook:**
   Open and run `DM_Project.ipynb` in Jupyter.

### Using the Project
Once the Jupyter Notebook is open, you can run the cells to execute the following steps:

1. **Data Extraction and Loading:**
   - Extract data from the CDC and US Census APIs.
   - Load the data into local or Google Cloud BigQuery tables.

2. **Data Cleaning and Preprocessing:**
   - Handle missing values and correct data types.
   - Normalize and transform data for analysis.

3. **Exploratory Data Analysis:**
   - Analyze death rates by sex, age group, and jurisdiction.
   - Identify trends and patterns in COVID-19 deaths.

4. **Data Validation:**
   - Ensure data integrity through validation checks.
   - Document data quality and any actions taken to address issues.

5. **Data Analysis with SQL Queries:**
   - Perform complex analytical queries to derive insights.
   - Use joins, window functions, and nested queries to explore data relationships.

6. **Visualization in Looker Studio:**
   - Create dashboards and reports to visualize key findings.
   - Use charts and graphs to effectively communicate insights.

### Key Findings
- **Vulnerable Groups:** Identified age groups and sexes most affected by COVID-19.
- **Geographic Patterns:** Analyzed state-wise variations in death rates and their correlation with population data.
- **Trend Analysis:** Observed temporal trends in death rates to understand the impact of different COVID-19 waves.

### Contributing to the Project
To contribute, follow these steps:
1. **Fork the repository.**
2. **Create a branch:**
   ```sh
   git checkout -b <branch_name>
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -m '<commit_message>'
   ```
4. **Push to the original branch:**
   ```sh
   git push origin <project_name>/<location>
   ```
5. **Create a pull request.**

### License
This project is licensed under the @2023 Surya Varma Vegesna.

### Contact
If you have any questions or want to contribute, please email us at surya@example.com.
