# WONG SI IEONG — Data Science Portfolio

## About Me
I am a Data Science student at the University of Macau. I am developing skills in Python, data analysis, and visualization, and my projects focus on turning a research question into a clear, reproducible analysis.

## Technical Skills
- **Programming**: Python, pandas, numpy, basic SQL
- **Visualization**: matplotlib, seaborn, squarify
- **Tools**: Jupyter Notebook, Anaconda, Git/GitHub
- **Data analysis**: data cleaning, exploratory data analysis, statistical plotting

## Featured Project: Education, Salary and Working Hours Analysis

### Research Question
Does a higher education level correspond to a higher annual salary, and how does education relate to weekly working hours? The analysis compares workers across five education groups, from "No diploma" to "Bachelor's degree or higher".

### Approach
I used pandas to load the course dataset and filter to workers aged under 65. I then summarized each education group by sample size, salary median and mean, and weekly hours median and mean. A treemap shows how the sample is distributed across education groups, and violin plots compare the salary and weekly hours distributions between groups.

### Visualization
![Treemap showing the share of each education group in the sample](images/treemap_education.png)

![Violin plots comparing annual salary and weekly hours by education level](images/violin_salary_hours.png)

### Findings
- Workers with a **Bachelor's degree or higher** have the highest salary distribution: median 61,000 and mean about 89,963 (n = 195).
- The other four groups have salary medians between about 20,400 and 38,000. Salary does not increase monotonically with education, and the "No diploma" group is small (n = 11).
- Weekly working hours are similar across groups (median 37–40 hours); the data do not show a clear monotonic relationship between education and hours.

### Limitation
This is observational data, so the plots show correlation rather than causation. Age, industry, and location are not controlled for. The dataset contains zero salary and zero hour values that were kept rather than separately coded, and some education groups are small. The currency unit is not stated in the source file.

### Project Repository
[View the code and README](https://github.com/wongsiieong/data-science-project)

### Status
Completed
