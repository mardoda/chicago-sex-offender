# Chicago Sex Offender Data Analysis

## Introduction
This project explores the characteristics of registered sex offenders in Chicago, focusing on male offenders due to their predominance in the dataset. The data is sourced from the city of Chicago's official website and includes over 1,000 records, though it is anonymized and certain demographic details are omitted for privacy.

## Dataset
- **Source**: City of Chicago's website
- **Scope**: Includes male sex offenders only
- **Records**: 1,000+ entries
- **Features**: 31, including numerical transformations of 'Height', 'Weight', and 'Age'

## Data Cleaning
- **Exclusions**: Female offenders are removed due to their minimal representation.
- **Duplicates**: Duplicate records are removed.
- **Column Adjustments**: Unnecessary columns such as names, blocks, and gender are dropped.
- **Racial Grouping**: Black and White Hispanics are combined into a single 'Hispanic' category.
- **Data Type Conversions**: Numeric conversion for 'Height', 'Weight', and 'Age'.
- **Height Adjustments**: Heights are standardized to inches only, correcting formatting issues and errors.

## Analysis Techniques
- **Demographic Analysis**: Focus on race, age, and victim age categories.
- **Statistical Visualization**: Use of charts to represent data distributions and correlations.
  
## Key Insights
- **Demographic Trends**: Overwhelming number of offenders are black, followed by white and Hispanic populations.
- **Age Distribution**: Sex offenders predominantly fall within the 35-60 age range.
- **Victim Age Analysis**: A significant majority of the victims are minors, with variations observed across racial groups.

## Results
- **Height and Weight Correlation**: Taller and heavier offenders tend to have adult victims.
- **Racial Disproportionality**: Black offenders are disproportionately higher in number and more likely to have adult victims.

## Conclusion
The analysis reveals critical insights into the demographics and characteristics of sex offenders in Chicago, highlighting key areas for potential policy intervention and further research.

