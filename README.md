## Jet Airline Safety Data Analysis

## Project Overview

This project analyzes historical aviation accident data to identify aircraft manufacturers and airplane types associated with lower passenger injury rates and lower aircraft destruction rates. The objective is to provide data-driven recommendations for a client seeking safer aircraft options for business operations.

The project follows a complete data science workflow consisting of:

- Data cleaning and preprocessing
- Feature engineering
- Exploratory Data Analysis (EDA)
- Statistical summaries
- Data visualization
- Business recommendations


## Business Problem

The client would like to purchase aircraft and wants recommendations based on historical aviation accident data. The analysis focuses on identifying manufacturers and airplane models that demonstrate lower rates of serious or fatal passenger injuries and lower rates of aircraft destruction.


## Dataset

Source:

- National Transportation Safety Board (NTSB) Aviation Accident Database
- Kaggle Aviation Accident Dataset


## Project Structure


.
├── data/
│   ├── AviationData.csv
│   └── AviationData_Clean.csv
│
├── Aviation_Accidents_Cleaning.ipynb
├── Aviation_Accidents_Data_Analysis.ipynb
├── README.md
```

---

## Data cleaning

The cleaning notebook performs the following tasks:

- Inspect missing values and data types
- Filter professional airplane records
- Remove aircraft older than the required period
- Handle missing injury values
- Estimate total passengers
- Create injury severity metrics
- Create aircraft destruction indicator
- Clean manufacturer and model names
- Create unique aircraft identifiers
- Remove columns with excessive missing values
- Export cleaned dataset

---

## Exploratory Data Analysis

The analysis notebook explores:

### Aircraft Makes

- Mean serious/fatal injury rate
- Aircraft destruction rate
- Small vs large airplanes
- Distribution of injury rates

### Aircraft Types

- Mean injury rates by make-model
- Distribution of injury severity
- Aircraft type comparisons

### Additional Factors

- Weather Condition
- Phase of Flight

Each analysis includes visualizations and business recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Findings

Some of the key insights include:

- Weather conditions significantly influence accident severity.
- Instrument Meteorological Conditions (IMC) are associated with substantially higher injury and aircraft destruction rates than Visual Meteorological Conditions (VMC).
- Accident severity varies considerably across different phases of flight.
- Certain aircraft manufacturers consistently demonstrate lower passenger injury rates than others.
- Aircraft destruction rates complement passenger injury metrics when evaluating aircraft safety.

---

## Repository

This repository contains:

- Data cleaning notebook
- Exploratory analysis notebook
- Cleaned dataset
- Project documentation


