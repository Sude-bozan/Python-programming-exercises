# Nobel Prize Dataset Analysis Project

This project is a comprehensive analysis of the Nobel Prize dataset, focusing on data manipulation, filling missing values, and visualization. The analysis is done using Python, with libraries like `pandas` and `matplotlib`.

## Project Overview

In this project, we explored the Nobel Prize dataset to gain insights into the distribution of prizes, trends over time, and the impact of socio-political factors on prize distribution. The dataset includes categories such as **motivation**, **organization name**, **birth country**, **birth date**, and **prize** categories.

### Key Tasks

1. **Data Cleaning**:
   - Identified and handled missing values across several columns.
   - Filled missing values in the `motivation` and `prize` columns based on related entries, ensuring data consistency.

2. **Data Manipulation**:
   - Used logical conditions to fill missing entries in the `organization_name`, `organization_city`, and `organization_country` fields.
   - For Nobel laureates who passed away before receiving the prize, filled in organization details based on birth country and city.

3. **Data Enrichment**:
   - Populated empty `birth_country` fields using related `organization_country` data.
   - Used average birth dates to fill missing values, categorized by 20-year periods.

4. **Data Visualization**:
   - Created various visualizations to understand trends, such as prize distribution across countries and age groups.
   - Showcased the impact of historical events (like World War II) on the Nobel Prize distribution.

### Insights

- **Country Trends**: Countries like the USA, UK, and Germany showed significant Nobel Prize achievements, with the USA experiencing a notable rise post-1940s.
- **Impact of World Events**: Nobel Prizes were not awarded during World War II, which is reflected as gaps in the dataset. The aftermath of wars and economic conditions also affected prize distributions.
- **Gender and Age Analysis**: Male laureates in the 60-90 age range were the most awarded, while younger female laureates were more common in fields like chemistry.

### Sample Visualizations

Here are a few examples of visualizations created in this project:
- **Nobel Prize Distribution by Country**: A bar chart showing the top countries with the highest Nobel Prize counts.
- **Age Analysis**: Line charts depicting the age distribution of Nobel Prize winners by category and gender.
- **Impact of World Wars**: Visualization of Nobel Prize counts over time, highlighting the influence of significant historical events.

### Conclusion

This project provides a detailed analysis of the Nobel Prize dataset, showing the influence of education, politics, and socio-economic conditions on prize distribution. It also highlights the changing trends in laureate demographics over time.

## Requirements

To run the code in this project, you need the following Python packages:
- `pandas`
- `matplotlib`

## How to Run

Clone this repository and navigate to the project directory. Run the Jupyter Notebook file to view the code and visualizations.

```bash
git clone <repository-url>
cd <repository-directory>
jupyter notebook Nobel_Prize_Analysis.ipynb
