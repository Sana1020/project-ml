# Student Performance Analysis & Prediction

A comprehensive machine learning project for analyzing and predicting student academic performance based on various socioeconomic and behavioral factors.

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project leverages machine learning techniques to analyze student performance data and build predictive models. By examining relationships between various student characteristics, study habits, and socioeconomic factors, we aim to identify key drivers of academic success and develop accurate prediction models for student grades.

## Dataset

The dataset contains comprehensive information about student demographics, study habits, and academic performance across multiple subjects.

### Attributes

| Feature | Description |
|---------|-------------|
| `student_id` | Unique identifier for each student |
| `age` | Student's age |
| `gender` | Student's gender |
| `school_type` | Type of school (public/private) |
| `parent_education` | Highest education level of parents |
| `study_hours` | Average daily study hours |
| `attendance_percentage` | School attendance percentage |
| `internet_access` | Whether student has internet access |
| `travel_time` | Time taken to reach school |
| `extra_activities` | Participation in extracurricular activities |
| `study_method` | Primary study method (notes/textbook) |
| `math_score` | Mathematics subject score |
| `science_score` | Science subject score |
| `english_score` | English subject score |
| `overall_score` | Average score across all subjects |
| `final_grade` | Final letter grade (a/b/c/d/e) |

## Project Structure

```
project ml/
├── Readme.md                      # Project documentation
├── Student_Performance.csv        # Dataset file
├── Student_Performance.ipynb      # Jupyter notebook with analysis

```

## Features

✅ **Data Exploration & Analysis**
- Comprehensive exploratory data analysis (EDA)
- Statistical summaries and distributions
- Correlation analysis between features and performance

✅ **Data Preprocessing**
- Missing value handling
- Duplicate row removal
- Feature encoding (categorical to numerical)
- Data normalization and scaling

✅ **Feature Engineering**
- Categorical variable encoding
- Feature selection and scaling
- Data transformation for model compatibility

✅ **Model Development**
- Classification models for grade prediction
- Performance evaluation and metrics
- Model comparison and optimization

## Installation

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Dependencies

Install required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**Required Libraries:**
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `scikit-learn` - Machine learning algorithms

## Usage

### Running the Analysis

1. **Clone or download the project**
   ```bash
   cd "project ml"
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Student_Performance.ipynb
   ```

3. **Execute cells sequentially** to run:
   - Data loading and exploration
   - Preprocessing and cleaning
   - Feature encoding
   - Model training and evaluation

### Project Workflow

The notebook follows this structured workflow:

1. **Import Libraries** - Load necessary Python packages
2. **Load Data** - Read the CSV dataset
3. **Exploratory Analysis** - Understand data structure and statistics
4. **Data Cleaning**
   - Detect and handle missing values
   - Remove duplicate records
   - Drop irrelevant features
5. **Feature Engineering**
   - Encode categorical variables
   - Scale numerical features
6. **Model Development**
   - Split data into training and testing sets
   - Train classification models
   - Evaluate performance metrics
7. **Results & Insights** - Analyze findings and conclusions

## Results

The analysis provides insights into:
- Key factors influencing student performance
- Relationships between socioeconomic factors and academic success
- Predictive models for grade classification
- Performance metrics and model accuracy

## Technologies

- **Python 3** - Programming language
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Scikit-learn** - Machine learning
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Contributing

Contributions are welcome! Please feel free to:
- Submit issues for bugs or suggestions
- Fork the repository and create pull requests
- Improve documentation or add new features

## License

This project is open source and available under the MIT License. Feel free to use it for educational and research purposes.
Author /Sana Elbakry
---

**Last Updated:** May 2026

For questions or support, please open an issue in the project repository.
