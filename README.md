# Wine Analysis Project

This project aims to analyze a dataset containing various attributes of wines and their associated quality ratings. The dataset includes columns such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol content, quality, and an identifier.

## Insights

### 1. Alcohol and Volatile Acidity Relationship
- There exists an inverse relationship between alcohol content and volatile acidity. As alcohol content increases, volatile acidity tends to decrease, impacting wine quality inversely.

### 2. Residual Sugar and Chlorides Behavior
- Residual sugar and chlorides demonstrate similar behavior, suggesting a potential correlation between these attributes.

### 3. Citric Acid and Quality Anomalies
- Many wines with a quality rating of 7 exhibit 0% citric acid content, indicating potential outliers or anomalies in the dataset.

### 4. Density Distribution
- The average density remains consistent across different quality ratings, as evidenced by the histogram indicating a normal distribution. The histogram also shows "ND Curve".

### 5. Outliers Detection
- Outliers are observed in attributes such as chlorides, residual sugar, and sulphates, suggesting potential data anomalies or extreme values that may impact the analysis results.

## Conclusion
This analysis provides valuable insights into the relationships between various attributes of wines and their quality ratings. Further exploration and statistical analysis can help in understanding the underlying factors influencing wine quality and refining predictive models.

## Tools and Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset used in this analysis is provided in the file `wine_dataset.csv`, containing the following columns:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality
- Id

## How to Run the Analysis
To reproduce the analysis and explore the insights further:
1. Install the required dependencies listed in `requirements.txt`.
2. Clone this repository to your local machine.
3. Open the Jupyter Notebook `wine_analysis.ipynb` using Jupyter Notebook or JupyterLab.
4. Run the notebook cell by cell to execute the analysis and visualize the results.

## Contributors
- [Sudhir Patil]

