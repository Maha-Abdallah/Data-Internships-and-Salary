# Data-Internships-and-Salary

## Data Science and Analytics Internships and Salaries Analysis

### Overview
This project aims to analyze a dataset containing information about data science and analytics internships and their corresponding salaries. The analysis includes data cleaning, descriptive statistics, visualizations, and a machine learning model to predict salaries based on company scores.

### Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/emreksz/data-science-and-analytics-internships-and-salaries). It contains the following columns:
- **Company**: Name of the hiring company.
- **Company Score**: Average rating of the company, as provided by Glassdoor.
- **Job Title**: Title of the internship position.
- **Location**: Job location, including city and state (or if remote).
- **Salary**: Estimated salary range for the internship position, as listed by the employer or Glassdoor.

### Project Structure
1. **Data Cleaning**: Handling missing values and converting salary data to a numeric format.
2. **Descriptive Statistics**: Generating summary statistics to understand the distribution of data.
3. **Visualizations**:
   - **Salary Distribution**: Histogram to visualize the distribution of salaries.
   - **Company Score vs. Salary**: Scatter plot to explore the relationship between company scores and salaries.
   - **Top Companies Word Cloud**: Word cloud visualization for the top 20 companies with a score greater than 4.5.

### Visualizations
- **Salary Distribution**: A histogram showing the frequency distribution of salaries.
- **Company Score vs. Salary**: A scatter plot illustrating the relationship between company scores and salaries.
- **Top Companies Word Cloud**: A word cloud highlighting the top 20 companies with high scores.

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ds-analytics-internships-salaries.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python analysis.py
   ```

### Conclusion
This project provides insights into the factors influencing internship salaries in the data science and analytics field. The visualizations and machine learning model offer a comprehensive understanding of the dataset.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
