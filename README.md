# Unicorn Companies Analysis

This project focuses on analyzing a dataset of unicorn companies, exploring their valuations, industries, time taken to reach unicorn status, and more. It includes data cleaning, transformation, and visualization to gain insights into the growth and trends of these companies.

## Dataset

The dataset contains information about unicorn companies, including:
- Company Name
- Valuation
- Date Joined
- Industry
- City
- Country/Region
- Continent
- Year Founded
- Funding
- Select Investors

**Dataset Source**: [Path to dataset, if applicable]

## Project Overview

### Goals
- Analyze the growth and trends of unicorn companies.
- Explore the time taken by companies in various industries to reach unicorn status.
- Visualize the distribution of maximum valuations across different industries.

### Key Steps
1. **Data Loading and Preprocessing**:
   - Loaded the dataset using pandas.
   - Performed initial data exploration with `df.head()`, `df.info()`, and `df.describe()`.
   - Converted the 'Date Joined' column to `datetime` format for better time-based analysis.
   - Added a new column 'Year Joined' derived from the 'Date Joined' column.

2. **Data Sampling**:
   - Took a random sample of 50 entries for further evaluation to reduce computational load and focus on specific analysis.

3. **Analysis and Visualization**:
   - Analyzed the time taken by companies to reach unicorn status (calculated as `Year Joined - Year Founded`).
   - Visualized this using a bar plot to compare across different industries.
   - Extracted and visualized the maximum valuation of companies in each industry.

## Visualizations

### Time Taken by Industry to Reach Unicorn Status
![Year taken by industry to be Unicorn](path/to/your/plot1.png)

### Maximum Unicorn Company Valuation per Industry (Sample)
![Maximum valuation in billions per industry](path/to/your/plot2.png)

## Libraries Used
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **datetime**: For handling date-time conversions.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/unicorn-companies-analysis.git
