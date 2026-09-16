
# Body Measurements Analysis of Adult Males and Females Using Python

## Project Overview

In this project, I analyse body measurement data of adult males and females using Python. I use NumPy, Matplotlib, Pandas, and SciPy to perform numerical calculations, create graphs, and understand the relationships between different body measurements.

The main focus of this project is to compare male and female weight distributions, calculate BMI, analyse body measurement ratios, and study correlations between different measurements.

## Objectives

- Read male and female body measurement datasets using NumPy.
- Create histograms and boxplots to compare weight distributions.
- Calculate statistical measures such as mean, median, standard deviation, skewness, and kurtosis.
- Calculate Body Mass Index (BMI) for female participants.
- Standardise the female body measurement data using z-scores.
- Create a scatterplot matrix to study relationships between measurements.
- Calculate Pearson's and Spearman's correlation coefficients.
- Calculate waist-to-height ratio and waist-to-hip ratio.
- Compare body measurement ratios using boxplots.
- Understand the advantages and disadvantages of BMI and body measurement ratios.

## Technologies and Libraries Used

- Python
- NumPy
- Matplotlib
- Pandas
- SciPy
- Jupyter Notebook

## Dataset

The datasets contain body measurements of adult males and females.

Each original dataset contains seven columns:

| Column | Measurement |
|---|---|
| 1 | Weight (kg) |
| 2 | Standing Height (cm) |
| 3 | Upper Arm Length (cm) |
| 4 | Upper Leg Length (cm) |
| 5 | Arm Circumference (cm) |
| 6 | Hip Circumference (cm) |
| 7 | Waist Circumference (cm) |

Additional columns are added during the analysis for BMI, waist-to-height ratio, and waist-to-hip ratio.

## Analysis Performed

### 1. Weight Distribution

I create histograms and boxplots to compare the weight distributions of male and female participants.

### 2. Statistical Analysis

I calculate measures of location, dispersion, and shape to understand the distributions.

### 3. BMI Calculation

I calculate BMI using weight and height and add it as a new column to the female dataset.

### 4. Data Standardisation

I convert the female measurements into z-scores to compare different variables on a common scale.

### 5. Correlation Analysis

I use Pearson's and Spearman's correlation coefficients to study the relationships between height, weight, waist circumference, hip circumference, and BMI.

### 6. Body Measurement Ratios

I calculate waist-to-height ratio and waist-to-hip ratio for both males and females.

### 7. BMI-Based Comparison

I identify the five participants with the lowest BMI and the five participants with the highest BMI, and print their standardised body measurements.

## Project Structure

```text
Body_Measurements_Analysis/
│
├── Body_Measurements_Analysis.ipynb
├── nhanes_adult_male_bmx_2020.csv
├── nhanes_adult_female_bmx_2020.csv
└── README.md
```

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install numpy matplotlib pandas scipy
   ```

3. Keep both CSV files in the same folder as the Jupyter Notebook.
4. Open `Body_Measurements_Analysis.ipynb`.
5. Run the code cells in order.
6. Check the generated graphs and numerical results.

## Results

The project provides visual and numerical comparisons of body measurements between adult males and females.

The graphs and statistical calculations help me understand weight distributions, body measurement relationships, and the use of BMI and body measurement ratios in data analysis.

## References

- Centers for Disease Control and Prevention (CDC) – BMI calculation.
- World Health Organization (WHO) – Waist circumference and waist-to-hip ratio.
- NumPy Documentation.
- Matplotlib Documentation.
- Pandas Documentation.
- SciPy Documentation.
