# CAR SALES ANALYSIS PROJECT

## Introduction
This project analyzes the Car Sales Dataset, which includes data on various car models, manufacturers, and other features in relation to their sales and pricing. The analysis addresses the following questions:

1. Which manufacturer has the highest and lowest average sales volume?
2. How are car prices distributed?
3. Is there a correlation among the numerical variables in the dataset?
4. Which are the most popular car brands?
5. What are the top 3 fuel-efficient cars with an engine size above 2.5 liters?

The goal of this analysis is to assess trends in car production, pricing, and efficiency over the years, using Python for data visualization and statistical analysis.

## Data Sourcing
The dataset was obtained from a Google Drive link shared in a WhatsApp group as part of the fourth assessment in the PSP Data Analytics class, facilitated by Mr. Joseph Elijah. The folder contained a CSV file of car sales data and an assessment question file.

## Data Preparation
The Python environment was prepared by importing the following libraries:

- **NumPy**: for numerical operations
- **Pandas**: for data manipulation and analysis
- **Matplotlib** and **Seaborn**: for data visualization

The data was read in CSV format and prepared for analysis.
![image](https://github.com/user-attachments/assets/941597fd-d971-4f86-9246-3f032b79b098)

## Data Exploration
### Initial Checks
1. **Rows and Columns**: The dataset contains 157 rows and 16 columns.
2. **Data Types**: The `dtypes` function was used to check data types, revealing that string columns are classified as "objects," numerical columns as "float," and the "Launch_date" column as an object instead of a datetime type.
3. **Missing Values**: The `.isna()` function was used to identify and count missing values.
![image](https://github.com/user-attachments/assets/035d25c3-5de9-499e-afc2-e140e6d98706)

## Data Cleaning
### Handling Missing Values
- The "year_resale_value" column had approximately 36 null values, which were replaced with the average of the column.
- Rows with other missing values were dropped.

### Renaming Columns
- The "year_resale_value" column was cleaned by removing leading underscores.

### Duplicates Check
- A check for duplicates revealed no duplicates present in the dataset.

## Descriptive Statistics
Descriptive statistics for the numerical columns were conducted using the `describe()` function, providing insights into mean, median, mode, and other metrics.
![image](https://github.com/user-attachments/assets/01912394-0ab0-407d-8f45-8e546dffec83)

## Exploratory Data Analysis (EDA)
1. **Average Sales Volume by Manufacturer**:
   - Manufacturers were grouped by average sales (in thousands) and sorted to identify the highest (Ford) and lowest (Porsche) average sales volume.
![Screenshot 2024-10-10 154235](https://github.com/user-attachments/assets/1ffdba6c-d954-478d-9a08-5241b56af859)

2. **Price Distribution**:
   - A plot was created showing the distribution of car prices by manufacturer.
    ![image](https://github.com/user-attachments/assets/6112e487-bd4c-42e9-8779-8737a944e401)


3. **Correlation Matrix**:
   - A correlation matrix was generated for the numerical variables, highlighting relationships among them.
  ![image](https://github.com/user-attachments/assets/a5aed24f-8d36-4bcc-b4e5-578b913b7ccf)


4. **Most Popular Car Brands**:
   - Ford, particularly the F-Series model, emerged as the most popular car brand based on maximum sales.
  ![image](https://github.com/user-attachments/assets/2afd5ceb-eb82-4b8e-8ba4-5516fa780eee)


5. **Top 3 Fuel-Efficient Cars**:
   - The top 3 fuel-efficient cars with engine sizes above 2.5 liters were identified as the Chevrolet Impala, Chevrolet Monte Carlo, and Mercedes CLK Coupe.
![image](https://github.com/user-attachments/assets/5743c0b0-9653-479d-92cd-32c4c402ba45)


## Conclusion and Recommendations
The analysis provided valuable insights into car sales trends. Key findings include:

- **Sales Performance**: Ford dominates the market with the highest average sales volume.
- **Price Trends**: Car prices show varying distributions among manufacturers.
- **Efficiency**: Specific models stand out for fuel efficiency, suggesting potential market opportunities.

Recommendations for further analysis include expanding the dataset for deeper insights and utilizing advanced visualization tools like Power BI for enhanced presentations.

---

For further inquiries or additional details regarding this analysis, please contact me.
