# Students grade prediction 🧑‍🎓

### Objective 🎯
Prediction of the final grade of Portugese high school students. 

### Description Of Dataset 📊 
The dataset contains attributes of 1044 Portuguese students from two Portuguese schools. The data has 32 attributes such as: students demographic features (like sex, age), social features (like family size, parents job and their level of education) and school-related features (grades, absences, studytime). The target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. 

### Methodology ⚙️
To predict grades, I performed a train-test split of 80:20. I trained LinearRegression, Random Forest Regressor, XGBoost Regressor, CatBoost Regressor, Decision Tree Regressor, GradientBoosting Regressor, Ridge and BayesianRidge, from the Sklearn library, on the training set. Grid Search CV was used to find optimal hyper-parameters for the models. Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
