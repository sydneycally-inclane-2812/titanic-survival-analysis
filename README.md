# Titantic Survival Analysis - A Data Science View
 
---
A data science project exploring the Titanic dataset to uncover factors influencing survival rates. This analysis utilizes data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling to predict passenger outcomes.

## Key findings

After analyzing and visualizing the data, there are a few notable points:
- Men are drastically less likely to survive than women aboard the ship.
- Rank and title largely does not influence survival.
- The embarking location does somewhat determine survival. 
- The fare was fairly cheap, although the ship itself was a breakthrough at the time and fitted with the most luxurious decorations.
- XGBoost provided the most accurate prediction on the test set.

## Data distribution after cleaning

![image](https://github.com/sydneycally-inclane-2812/billionaires-mile-low-club/assets/98740915/32c355a5-982c-4502-b5e2-d997b07f2eeb)


## Methods used

Data cleaning and preparation, feature engineering
Models used: LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, SVC, KNN, GradientBoostingClassifier, XGBoost, Tensorflow

## How to run the project

1. Install the necessary libraries:
    ```
    pip install tensorflow xgboost 
    ```
2. Make sure Scikit-learn is at its latest version:
    ```
    pip install --upgrade scikit-learn 
    ```
3. Clone Repository:
    ```
    git clone https://github.com/sydneycally-inclane-2812/billionaires-mile-low-club.git
    ```
4. Run each cell in the .ipynb file in order.

## Future Direction

Some things can definitely be improved, from removing irrelevant data to hyperparameter tuning for some models.
One thing I try to do is use all the models built to make an ensemble, taking the output of the majority to get the most accurate results.

## Contributing

Feel free to contribute to this project! Suggestions, improvements, and extensions are welcome.

Fork the repository.
Create a feature branch.
Make your changes.
Submit a pull request.

## License

This project is released under the Apache License 2.0.

Let me know if you'd like to modify any sections, add specific details, or adjust the focus!
