# random-regration
# Ordinal Encoding in Machine Learning

This project demonstrates how to perform **Ordinal Encoding** on categorical data using Python, pandas, and scikit-learn. Ordinal encoding is useful when the categories have a meaningful order, such as education level or work experience.

## 📁 File Structure

- `ml.py` - Main Python script that performs ordinal encoding on a sample dataset.

## 📊 Dataset Description

The sample dataset contains two categorical features:

- `Education`: ['High School', 'Bachelor', 'Master', 'PhD']
- `Experience`: ['Junior', 'Mid', 'Senior']

These columns have a natural order and are suitable for ordinal encoding.

## 🧠 Ordinal Encoding Logic

The following order is defined for encoding:

- **Education Order**:  
  `High School < Bachelor < Master < PhD`

- **Experience Order**:  
  `Junior < Mid < Senior`

We use `OrdinalEncoder` from `sklearn.preprocessing` to convert these ordered categories into numeric values.

## 🛠 Requirements

To run the code, make sure you have the following Python libraries installed:

```bash
pip install pandas scikit-learn



## Author
payal Tanaji Chougale
Final year Computer Engineering Student
Email: payaltchougale@1911gmail.com

