# EDA on Adult Income

## Description
This project involves performing Exploratory Data Analysis (EDA) on the **Adult Income** dataset. The dataset, sourced from the UCI Machine Learning Repository, contains demographic and income information. The goal is to explore the features, visualize trends, handle missing values, and derive insights about the factors that influence whether a person earns more or less than $50,000 per year.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/Daivik2605/EDA-on-Adult-Income
cd EDA-on-Adult-Income
pip install pandas matplotlib seaborn

```

## Usage
You can run the analysis in a Jupyter Notebook by opening the provided `.ipynb` file. The dataset is loaded and explored through various visualizations and techniques.

Example:
```bash
jupyter notebook eda_adult_income.ipynb
```

## Features
- **Data Cleaning**: Handled missing values and duplicates.
- **Data Visualization**: Visualized distributions of age, gender, education, and other features relative to income.
- **Handling Outliers**: Identified and addressed outliers in key features.
- **Correlation Analysis**: Analyzed the relationships between different features.
- **Insights**: Derived patterns and trends about income distribution based on demographic factors.

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: Data manipulation.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive development environment.

## Results
Key insights from the analysis:
- Income distribution is heavily influenced by education level and work hours.
- Most individuals who earn less than $50k are between the ages of 18 and 30, while those earning more than $50k are predominantly aged between 35 and 55.
- There is a significant gender disparity, with more males earning above $50k.
- Class imbalance is present in the dataset, with a higher number of records for individuals earning less than $50k.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you’d like to improve the project.

## Acknowledgments
- Data Source: [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult).
- Inspired by various data exploration techniques learned from online resources and tutorials.
