# Lung Cancer Prediction & Analysis

## Overview
This project focuses on analyzing and predicting lung cancer diagnosis using a comprehensive dataset containing information about patients from various countries, their lifestyle factors, environmental exposures, and treatment outcomes.

## Project Structure
## Dataset Features
The dataset includes the following features:

**Demographics:**
- Country
- Gender
- Developed/Developing country status

**Health Factors:**
- Smoker status
- Passive Smoker exposure
- Family History of lung cancer
- Lung Cancer Diagnosis (target variable)
- Cancer Stage (1-4)
- Adenocarcinoma Type

**Environmental Exposures:**
- Air Pollution Exposure
- Occupational Exposure
- Indoor Pollution

**Healthcare:**
- Healthcare Access
- Early Detection
- Treatment Type (Surgery, Chemotherapy, Radiotherapy)

## Data Processing
The notebook performs the following operations:

1. **Exploratory Data Analysis (EDA):**
   - Loads and examines dataset structure
   - Checks for missing values
   - Analyzes data types
   - Explores unique values and distribution

2. **Data Cleaning:**
   - Encodes categorical variables
   - Handles missing values using median imputation
   - Maps numerical values back to categorical labels

3. **Data Export:**
   - Exports cleaned data to `cleaned_data.csv` for further analysis or modeling

## Technologies Used
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Jupyter Notebook** - Interactive analysis environment

### Prerequisites
```bash
pip install pandas numpy jupyter
