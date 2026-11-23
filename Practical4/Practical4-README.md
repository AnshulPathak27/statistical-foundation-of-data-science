# Practical 4: Data Analysis and Visualization using Python

## Aim
To perform data cleaning, statistical analysis and data visualization on the Teaching Ratings dataset using Python.

## Libraries Used
- **Pandas:** For data manipulation, filtering and statistical analysis.
- **NumPy:** For numerical operations.
- **Matplotlib:** For creating graphs and visualizations.

## Dataset
The Teaching Ratings dataset is obtained from IBM Skills Network. It contains information about professors, including age, gender, teaching evaluation, tenure, course division and other details.

## Description

The following operations were performed:

1. Imported the required Python libraries.
2. Loaded the Teaching Ratings dataset using Pandas.
3. Displayed the first five rows using `head()`.
4. Identified duplicate observations for the same professor using `duplicated()`.
5. Calculated the average age and standard deviation of the complete dataset.
6. Removed repeated instructor records using `drop_duplicates()`.
7. Calculated age statistics for 94 unique professors.
8. Identified the available course division categories using `unique()`.
9. Calculated average teaching evaluation scores for lower and upper division courses.
10. Created a bar chart to compare average evaluations by course division.
11. Created a scatter plot to examine the relationship between age and teaching evaluation.
12. Compared age and evaluation patterns for male and female instructors.
13. Created separate scatter plots to analyse age and evaluation based on gender and tenure.

## Important Results

- Total unique professors: **94**
- Average age of the complete dataset: **48.37 years**
- Standard deviation of age: **9.80**
- Average evaluation for lower division courses: **4.09**
- Average evaluation for upper division courses: **3.95**

### Observations
- Lower division courses received slightly higher average teaching evaluation scores than upper division courses.
- No strong relationship was observed between professor age and teaching evaluation.
- Teaching evaluation scores varied across different age groups, genders and tenure statuses.

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

## Conclusion
Successfully performed data cleaning, statistical analysis and visualization on the Teaching Ratings dataset. Learned how to identify and remove duplicate records, calculate descriptive statistics, group data and analyse relationships between variables using bar charts and scatter plots.
