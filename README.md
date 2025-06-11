# titanic-cleaning-project
This project explores the titanic dataset and focuses on data cleaning
# 🚢 Titanic Dataset – Clean the Data

This project explores the Titanic dataset and focuses on data cleaning:

## 🔍 Cleaning Tasks Performed:
- Handled missing values in `Age`, `Embarked`
- Dropped `Cabin` due to high NULL rate
- Converted `Pclass`, `Sex`, `Embarked` to categorical
- Removed duplicates
- Saved cleaned dataset for future modeling

## 💡 Logical Fixes:
1. Filled `Age` with median
2. Dropped `Cabin` (too many missing)
3. Filled `Embarked` with mode
4. Changed data types (categorical fix)
5. Removed duplicate rows

## 📦 Tools Used:
- Python
- Pandas

## 📁 Output:
- `cleaned_titanic.csv`
- Cleaned dataset ready for modeling
