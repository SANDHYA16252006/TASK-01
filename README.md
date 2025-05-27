Task 1: Data Cleaning & Preprocessing - Titanic Dataset

Objective:
This task is part of the AI & ML Internship. The goal is to learn how to clean and prepare raw data for machine learning.


Dataset:
We used a version of the Titanic dataset (`train_and_test2.csv`) which contains information about passengers, including their survival status, demographics, and ticket details.


Tasks Completed:

1. Data Loading & Exploration
- Loaded the dataset using `pandas`
- Displayed top rows using `df.head()`
- Checked data types, null values, and basic statistics

2. Handling Missing Values
- Filled missing `Age` and `Fare` with their respective medians
- Filled missing `Embarked` values with the mode
- Handled missing `Cabin` by replacing with `"Unknown"` (if column exists)

3. Encoding Categorical Variables
- Label encoded `Sex` (female → 0, male → 1)
- One-hot encoded `Embarked` and dropped the first column to avoid the dummy variable trap

4. Feature Scaling
- Applied `StandardScaler` to `Fare` and `Age` columns to normalize them

5. Outlier Detection & Removal
- Used the IQR method to detect and remove outliers in the `Fare` column

6. Data Visualization
- Created boxplots to visualize outliers
- Generated a correlation heatmap to understand relationships between features


Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

