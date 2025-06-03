# Student Score Analysis 📊

## Overview

This project analyzes student performance data to uncover insights about factors that influence academic scores in Math, Reading, and Writing. The analysis explores relationships between student demographics, parental factors, and academic performance using comprehensive data visualization and statistical analysis.

### Key Findings
- **Gender Distribution**: Analysis reveals gender distribution patterns in the dataset
- **Parental Education Impact**: Strong correlation between parent education levels and student academic performance
- **Marital Status Effect**: Minimal to no impact of parental marital status on student scores
- **Ethnic Group Distribution**: Comprehensive breakdown of student demographics across different ethnic groups
- **Score Distribution**: Detailed analysis of outliers and score patterns across all subjects

## Dataset Features

The analysis covers the following student attributes:
- **Demographics**: Gender, Ethnic Group
- **Parental Factors**: Education Level, Marital Status
- **Academic Performance**: Math Score, Reading Score, Writing Score
- **Study Habits**: Weekly Study Hours

## Installation & Setup

### Required Libraries
```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install jupyter
```

### Alternative Installation
```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## Project Structure
```
Student-Result-Analysis/
├── Student_score_analysis.ipynb    # Main analysis notebook
├── Student_score_analysis.csv      # Dataset file
└── README.md                       # Project documentation
```

## Cloning the Repository

### Using HTTPS
```bash
git clone https://github.com/Jyothi-CY/Student-Result-Analysis.git
cd Student-Result-Analysis
```

### Using SSH
```bash
git clone git@github.com:Jyothi-CY/Student-Result-Analysis.git
cd Student-Result-Analysis
```

## How to Run

1. **Clone the repository** (see above)
2. **Install dependencies** using pip commands
3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
4. **Open the analysis notebook**: `Student_score_analysis.ipynb`
5. **Update the dataset path** in the notebook:
   ```python
   df = pd.read_csv("path/to/your/Student_score_analysis.csv")
   ```
6. **Run all cells** to execute the complete analysis

## Skills Demonstrated

### Technical Skills
- **Data Analysis**: Pandas for data manipulation and cleaning
- **Data Visualization**: Matplotlib and Seaborn for creating insightful charts
- **Statistical Analysis**: Groupby operations, aggregations, and correlation analysis
- **Data Cleaning**: Handling missing values, renaming columns, and data preprocessing

### Analytical Skills
- **Exploratory Data Analysis (EDA)**: Comprehensive dataset exploration
- **Pattern Recognition**: Identifying trends and relationships in student performance
- **Outlier Detection**: Using box plots to identify data anomalies
- **Comparative Analysis**: Cross-group comparisons using heatmaps and visualizations

### Visualization Techniques
- **Count Plots**: For categorical data distribution
- **Heatmaps**: For correlation analysis between variables
- **Box Plots**: For outlier detection and score distribution
- **Pie Charts**: For demographic distribution analysis
- **Bar Charts**: For frequency analysis with labeled values

## Analysis Highlights

### 1. Gender Distribution Analysis
Visual representation of male vs female student distribution in the dataset.

### 2. Parental Education Impact
Heatmap analysis showing strong correlation between parent education levels and student performance across all subjects.

### 3. Parental Marital Status Study
Statistical analysis revealing minimal impact of parental marital status on academic performance.

### 4. Ethnic Group Distribution
Comprehensive pie chart and count plot analysis of student demographics across different ethnic groups.

### 5. Score Distribution & Outliers
Box plot analysis identifying outliers in Math, Reading, and Writing scores.

## Key Insights

- **Parental Education**: Significant positive correlation with student academic performance
- **Marital Status**: No significant impact on student scores
- **Gender Balance**: Dataset shows specific gender distribution patterns
- **Score Patterns**: Detailed outlier analysis across all subject areas

## Future Enhancements

- Add correlation matrix analysis between all numerical variables
- Implement machine learning models for score prediction
- Include statistical significance testing
- Add interactive visualizations using Plotly
- Expand analysis to include study hours correlation

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or additional analysis features.
 
**Project Link**: [Student-Result-Analysis](https://github.com/Jyothi-CY/Student-Result-Analysis)
