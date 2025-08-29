# 📊 Data Analysis Report: Students Performance Dataset

## Task 1: Load and Explore the Dataset
- Dataset: **StudentsPerformance.csv**
- First few rows were displayed using `.head()`.
- Data types and structure checked using `.info()`.
- Missing values checked with `.isnull().sum()`.  
  - ✅ No missing values were found (after cleaning with `.dropna()`).

## Task 2: Basic Data Analysis
- Summary statistics of numerical columns computed using `.describe()`.
- Grouping performed on **parental level of education** to compute the average **math score**:
  - Higher parental education levels are associated with better math scores.
- Key Findings:
  - **Math, reading, and writing scores** are positively correlated.
  - Students with higher parental education levels tend to perform better across all subjects.

## Task 3: Data Visualization
1. **Line Chart**  
   - Cumulative math scores over student records.  
   - Shows overall trend of increasing totals as data accumulates.  

2. **Bar Chart**  
   - Average math score by parental education level.  
   - Students with *master’s degree parents* scored highest on average.  

3. **Histogram**  
   - Distribution of reading scores.  
   - Scores cluster around the 60–80 range, indicating a normal-like distribution.  

4. **Scatter Plot**  
   - Math score vs Writing score.  
   - Strong positive correlation: students good in math are usually good in writing too.  

## Observations
- **Parental education level** significantly impacts student performance.  
- **Reading and writing scores** show similar distributions, while math scores vary more widely.  
- Strong correlation between math and writing scores indicates overall academic consistency.  

---
✅ This analysis provides valuable insights into factors affecting student performance, which could help educators and policymakers design better support programs.
