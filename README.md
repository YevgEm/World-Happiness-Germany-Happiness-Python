# World-Happiness-Germany-Happiness-Python
This project analyzes global happiness trends from 2015 to 2023, with a special focus on Germany.

## Overview
This project analyzes global happiness trends from 2015 to 2023, with a special focus on Germany. Using datasets from the World Happiness Report, we explore key factors influencing happiness, including GDP per capita, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption.

## Data Sources
The datasets used in this analysis were obtained from the **World Happiness Report (2015-2023)**, publicly available on [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/world-happiness-report-2013-2023).

## Data Cleaning & Preprocessing
- **Merged** datasets from multiple years into a unified format.
- **Adjusted GDP per capita** values to ensure consistency across years.
- **Corrected discrepancies** in healthy life expectancy (especially for 2020-2023).
- **Handled missing values** and outliers in social support and perceptions of corruption.

## Key Findings & Insights

### Global Trends
- Countries with **higher GDP per capita and social support** tend to report **higher happiness scores**.
- **Perceptions of corruption** generally show a negative correlation with happiness.
- **Freedom to make life choices** is moderately correlated with happiness.

### Germany-Specific Insights
- **Happiness vs. Healthy Life Expectancy:** Moderate positive correlation (**0.42**), showing that a longer, healthier life is linked to higher happiness.
- **Happiness vs. Perceptions of Corruption:** A **moderate positive correlation (0.67)**—suggesting corruption perception in Germany doesn’t strongly diminish happiness levels.
- **Happiness vs. Social Support:** Unexpected **negative correlation**—likely influenced by pandemic-related policies in 2020.

### Statistical Analysis
- **Regression Analysis** was performed to examine the impact of different factors on happiness scores.
- **Clustering Analysis** helped identify distinct groups of countries based on happiness indicators.
- **Time Series Analysis** was conducted to observe trends and predict future happiness scores.

### Visualizations
#### Correlation Matrix (Germany 2015-2023)
![Correlation Matrix](https://github.com/user-attachments/assets/8ec99d41-62ed-4d43-9eb2-f9603bafd029)

#### Global Happiness Score Trends (2015-2023)
![Happiness Trends](https://github.com/user-attachments/assets/560b48ec-4742-4c43-9984-aacc8fbaf885)


## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **GitHub** for version control
- **Tableau** for additional visual storytelling

## How to Reproduce This Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/world-happiness-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook World_Happiness_Analysis.ipynb
   ```

## Author & Credits
- **Your Name** – Data Analysis & Visualization
- **Dataset Source:** [World Happiness Report on Kaggle](https://www.kaggle.com/datasets/joebeachcapital/world-happiness-report-2013-2023)

## Future Improvements
- Further refinement of social support data handling.
- More detailed time-series analysis.
- Deeper analysis of regional factors affecting happiness.
