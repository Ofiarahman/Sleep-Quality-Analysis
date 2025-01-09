# Sleep Quality Analysis

This repository contains a comprehensive analysis of sleep quality and its influencing factors using data from the `sleep_health_data.csv` dataset. The analysis explores the relationships between various lifestyle and physiological metrics, such as stress levels, physical activity, and heart rate, and their impact on sleep quality.

## Project Overview
The primary goals of this project include:

1. **Data Cleaning**: Removal of unwanted data of the dataset
2. **Data Exploration**: Understanding the structure and key features of the dataset.
3. **Visualization**: Highlighting trends and patterns across demographic and health metrics.
4. **Statistical Insights**: Identifying correlations and group-specific trends.
5. **Machine Learning**: Building a predictive model to estimate sleep quality based on key features.

## Key Findings

- **Occupational Trends**:
  - Scientists report the lowest average sleep quality, highest stress levels, and lowest physical activity levels.
- **BMI Category Insights**:
  - Obese individuals have significantly lower physical activity levels and daily steps compared to other BMI categories.
- **Gender Differences**:
  - Males have higher average stress levels than females.
- **Correlations**:
  - Sleep duration is positively correlated with sleep quality.
  - Stress levels and heart rate negatively impact sleep quality.

## Machine Learning Model
A linear regression model was created to predict the quality of sleep using:
- Stress Level
- Heart Rate
- Sleep Duration
- Physical Activity Level

### Model Performance
- **Mean Squared Error (MSE)**: *0.1474776370124222*
- **R-squared (R²)**: *Value*

These metrics indicate the model's effectiveness in capturing the relationships between features and sleep quality.

## Visualizations
The analysis includes:
- Bar plots comparing mean metrics across Occupations, BMI Categories, and Gender.
- A correlation heatmap showing relationships between numerical variables.
- Pair plots for detailed exploration of numerical features.

## Repository Structure
```
├── data
│   └── sleep_health_data.csv   # Dataset
├── notebooks
│   └── sleep_quality_analysis.ipynb   # Jupyter Notebook with analysis
├── README.md   # Project overview and findings
```

## Requirements
To replicate the analysis, install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Ofiarahman/sleep-quality-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sleep-quality-analysis
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/sleep_quality_analysis.ipynb
   ```

## Conclusion
This project highlights actionable insights into sleep quality determinants, emphasizing the importance of stress management and physical activity in improving sleep health. The findings can inform health policies and personalized wellness strategies.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- Data Source: [sleep_health_data/github]
- Tools: Python, Jupyter Notebook
