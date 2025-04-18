# Laptop Price Prediction 
This is a Machine Learning project focused on predicting laptop prices and exploring various insights from the dataset.
## Project Objectives:
### Brand Analysis
1. Identify the top 5 laptop brands by the number of products listed.
2. Calculate the average laptop price for each brand.
3. Identify the highest and lowest average priced brands.
### Feature Correlation:
4. Analyze the correlation between Price_euros and numeric features like:
   - CPU frequency (`CPU_freq`)
   - RAM
   - Screen size (`Inches`)
   - Weight
5. Identify which features are most correlated with price.

## Feature Engineering
6. Create a new feature:
   -StorageTotal = PrimaryStorage + SecondaryStorage
### Regression Modeling:
7. Build regression models using features like:
- RAM
- Inches
- CPU frequency
- Primary Storage
- GPU company
8. Predict Price_euros and suggest the best regression model based on performance.
## Classification Modeling:
9. Create a classification model to predict the laptop type (TypeName) based on:
-Inches
-Ram
-PrimaryStorage
-Weight
10. Identify the most important features and suggest the best classification model.
## Tools & Libraries Used:
- **Programming Language**: Python  
- **Data Manipulation**: `Pandas`, `NumPy`  
- **Visualization**: `Seaborn`, `Matplotlib`  
- **Machine Learning**: `Scikit-learn
