# AI Agent Instructions for Data Analysis Projects

This document provides essential guidance for AI agents working with this data analysis project collection. Each project follows consistent patterns while maintaining specific focus areas.

## Project Structure

The repository consists of multiple independent data analysis projects, each following a consistent structure:
```
Project-Directory/
  ├── dataset.csv          # Primary data source
  └── Project_Name.ipynb   # Jupyter notebook containing analysis
```

## Core Technologies

- **Primary Language**: Python
- **Key Libraries**: 
  - pandas: Data manipulation and analysis
  - plotly: Interactive visualizations
  - matplotlib/seaborn: Static visualizations
  - statsmodels: Time series analysis (SARIMA models)
  - numpy: Numerical computations

## Project Patterns

### Data Loading
Projects typically start with data loading from CSV files. Example pattern from `My-Project-DA01`:
```python
df = pd.read_csv('Electric_Vehicle_Population_Data.csv')
```

### Data Analysis Workflow
Each notebook follows this general structure:
1. Data Loading and Initial Exploration
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Statistical Analysis/Modeling
5. Visualization
6. Conclusions/Insights

### Visualization Conventions
- Interactive plots use Plotly
- Statistical plots use Seaborn
- Time series visualizations primarily use Plotly

## Project-Specific Focus Areas

1. **EV Market Analysis** (`My-Project-DA01`):
   - Geographic distribution analysis
   - Time series market growth analysis
   - Vehicle make/model distributions

2. **Social Media Analytics** (`My-Project-DA02`, `My-Project-DA05`):
   - Engagement metrics analysis
   - Time series forecasting
   - Content performance optimization

3. **Financial Analysis** (`My-Project-DA04`):
   - Stock price analysis
   - ROI calculations
   - Volatility assessment

## Best Practices

1. **Data Validation**:
   - Always check for missing values
   - Validate data types
   - Document any data quality issues

2. **Code Organization**:
   - Use markdown cells for section documentation
   - Include analysis rationale
   - Document key findings

3. **Memory Management**:
   - Use appropriate data types
   - Clear unnecessary variables when working with large datasets

## Common Workflows

1. **Adding New Analysis**:
   - Create new directory following naming convention (`My-Project-DA{XX}`)
   - Add dataset and Jupyter notebook
   - Follow established analysis pattern

2. **Updating Existing Analysis**:
   - Maintain consistent notebook structure
   - Document changes in markdown cells
   - Ensure visualizations follow project conventions