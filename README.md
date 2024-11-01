# 🎯OVERVIEW.
This repository houses my solutions for the Pandas checkpoint/assignment. The purpose of this assignment is to showcase my skills in data manipulation and analysis using the Pandas library in Python. This project covers Dataframe Filtering and Selection using iloc and loc.

# 📢DESCRIPTION.
The repository is organized into the following sections:
- The Python code.
- The ReadMe file.
In this Checkpoint, I worked with a dataset called "employee info" that contains information about employees in a company. The dataset includes columns such as Name, Department, Age, Gender, Salary, and Experience.

# ℹ️INSTRUCTIONS.
- Create a dataframe called "employee_df" with the following data:
- Use the iloc method to select the first 3 rows of the dataframe.
- Use the loc method to select all rows where the Department is "Marketing".
- Use the iloc method to select the Age and Gender columns for the first 4 rows of the dataframe.
- Use the loc method to select the Salary and Experience columns for all rows where the Gender is "Male".

Note:
- iloc is used for selection by index location
- loc is used for selection by label.

# 🛠️TOOLS USED.
- Anaconda.
- VSCode.
- Python.
- Git.
- GitHub.

```
import pandas as pd

data = {'Name': ['John', 'Mary', 'Bob', 'Sarah', 'Tom', 'Lisa'], 'Department': ['IT', 'Marketing', 'Sales', 'IT', 'Finance', 'Marketing'], 'Age': [30, 40, 25, 35, 45, 28], 'Gender': ['Male', 'Female', 'Male', 'Female', 'Male', 'Female'], 'Salary': [50000, 60000, 45000, 55000, 70000, 55000], 'Experience': [3, 7, 2, 5, 10, 4]}

employee_df = pd.DataFrame(data)
```
