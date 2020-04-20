# Identify Customer Segments with Arvato

This project is focused around unsupervised learning techniques. In it Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information of Germany and the other with that same demographic information but for customers of a mail-order sales company. I preprocess the data, perform dimensionality reduction using PCA, impliment KMeans clustering, and compare existing customers to the general population.

The data used in this project was not published due to licensing and Arvato's terms and conditions.

This project was completed as part of [Udacity's Introduction to Machine Learning Nanodegree](https://www.udacity.com/course/intro-to-machine-learning-nanodegree--nd229) certification.

# Libraries

Python version 3.6 and the following libraries were used:
- NumPy
- Pandas
- matplotlib
- scikit-learn==0.19
- seaborn

# Data

- `Udacity_AZDIAS_Subset.csv` : Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv` : Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md` : Information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv` : Summary of feature attributes for demographic data.
- `Identify_Customer_Segments.ipynb` : Jupyter Notebook divided into sections and guidelines for completing the project.