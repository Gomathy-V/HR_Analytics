# HR Analytics

### Project Description

- This project aims to analyze why employees are leaving the company using a comprehensive people dataset. The objective is to identify key factors contributing to employee departures and provide actionable insights to improve retention rates.

### Dataset
- The dataset contains detailed information about employees, including various job-related metrics and personal attributes as below,

   - **satisfactoryLevel:** Employee's self-reported job satisfaction level (scale 0-1)
   - **lastEvaluation:** The score of the employee's last evaluation (scale 0-1)
   - **numberOfProjects:** Number of projects the employee has worked on
   - **avgMonthlyHours:** Average number of hours worked per month by the employee
   - **timeSpentCompany:** Number of years the employee has been with the company
   - **workAccident:** Whether the employee has had a work accident (1 = Yes, 0 = No)
   - **left:** Whether the employee has left the company (1 = Yes, 0 = No, target variable)
   - **promotionInLast5years:** Whether the employee has been promoted in the last 5 years (1 = Yes, 0 = No)
   - **dept:** Department where the employee works
   - **salary:** Employee's salary level (low, medium, high)
 
### Tools and Technologies

- **Programming Languages:** Python
- **IDE/Code Editor:** Jupyter Notebook
- **Data Analysis Libraries:** Pandas, NumPy
- **Visualization Tools:** Matplotlib, Seaborn

### Data Cleaning & Preparation
- In the initial data preparation phase, we performed the following tasks:

  - Familiarizing with data and inspected data.
  - Handle duplicated data.
  - Data cleaning and formatting.

### Exploratory Data Analysis
- Performed an exploratory data analysis to visualize and analyze why employees are leaving the company.

#### EDA involved exploring the data in such a way that:

- Analyze the distribution of features.
- Identify trends and patterns.
- Visualize correlations between features and the target variable (left).
- Examine demographic breakdowns and their impact on departure rates.


### Insights

#### Project Assignment Analysis 

- The departure rate is highest among individuals handling either two or seven projects.

#### Insights on Tenure 

- The organization is seeing a increase in the number of employees leaving after 3-5 years.
- Those who have been with the company for more than 6 years tend to stay.

#### Review of Promotions

- Employees who have not been promoted in the last 5 years are departing in larger numbers.

#### Examination of Work Accidents

- Employees leaving is not significantly influenced by work accidents.

#### Assessment by Department

- In the highest numbers, employees from HR and accounting are leaving.

#### Evaluation of Salary

- Employees with lower to moderate salaries are departing in greater numbers, while those with higher salaries exhibit lower departure rates.

#### Study of Working Hours

- Employees working over 200 hours are leaving in larger numbers, particularly as they near the 300-hour threshold.


### Actionable Steps:

#### 1. Optimize project assignments

- **Issue:** Departure rate peaks among those managing two or seven projects.
- **Recommendation:** The average number of projects assigned to all employees should be 3-5.Redistribute the workload among employees handling two projects to balance out the workload from those handling seven projects.

#### 2. Reward Policy for Long-term Employees

- **Issue:** Employees are leaving the organization after 3-5 years.
- **Recommendation:** Upon completing 3-5 years, they should be rewarded with such things as hikes, better job positions, incentives, or increments.

#### 3. Addressing Attrition Through Timely Promotions

- **Issue:** Non-promoted employees in 5 years leaving more.
- **Recommendation:** Give promotions to all employees in a timely manner.

#### 4. Streamlining Workloads

- **Issue:** HR and accounting employees are leaving the most.
- **Recommendation:** Implement measures to reduce the workload of employees, thereby allowing them to achieve a better balance between work and personal life.

#### 5. Fair Compensation Policy

- **Issue:** Lower to moderate earners leave more; higher earners, less. 
- **Recommendation:** Provide employees with a salary that is fair and commensurate with their skills, experience, and contributions to the organization.

#### 6. Ensuring Reasonable Working Hours

- **Issue:** Employees logging over 200 hours leave more, especially nearing 300.
- **Recommendation:** Make sure that employees' working hours are reasonable, and refrain from asking them to work overtime.





