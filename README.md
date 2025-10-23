

# Contraceptive Method Usage Prediction 🤰👶📊

## Project Overview

This project is all about predicting which contraceptive method couples might use based on different factors like age, education, and lifestyle. We'll dive into the data 🧐, get it ready for analysis ✨, and build some cool models using Decision Trees 🌳 and Random Forests 🌲!

## Dataset

Our journey begins with the `Contraceptive_method_dataset.xlsx` file. It's packed with info about couples and their contraceptive choices. 💑

## Methodology

Here's the roadmap we followed:

1.  **Exploratory Data Analysis (EDA)**:
    *   Took a good look at the data's structure, types, and any missing pieces. 🕵️‍♀️
    *   Vizualized how numerical features are spread out with colorful histograms. 📈
2.  **Data Preprocessing**:
    *   Filled in those missing values for 'Wife\_age' and 'No\_of\_children\_born' using the median magic! ✨
    *   Turned text categories into numbers with one-hot encoding. 🔢
    *   Scaled our numerical features so they play nicely together. ⚖️
3.  **Train-Test Split**:
    *   Split our data into training and testing squads (80/20 split) to train and evaluate our models fairly. ✂️
4.  **Model Building and Training**:
    *   Built and trained a Decision Tree model. 🌳
    *   Built and trained a Random Forest model (it's like a forest of decision trees!). 🌲🌲🌲
5.  **Model Evaluation**:
    *   Tested our models on the unseen test data to see how well they perform. 🤔
    *   Calculated key metrics: accuracy, precision, recall, and F1-score. ✅🎯
    *   Created confusion matrices to see where our models got confused. 🤷‍♀️🤷‍♂️
6.  **Results and Summary**:
    *   Compared the performance of our Decision Tree and Random Forest models. 🏆
    *   Wrapped up all our findings and insights. 🎁

## Results

Here's how our models stacked up on the test data:

| Model          | Accuracy | Precision | Recall | F1-score |
| :------------- | :------- | :-------- | :----- | :------- |
| Decision Tree  | 0.6576   | 0.7105    | 0.6545 | 0.6814   |
| Random Forest  | 0.6915   | 0.7011    | 0.7818 | 0.7393   |

Looks like the Random Forest model 🌲 was the winner across the board! 🎉

**Confusion Matrix (Test Data) - Decision Tree:**
TP: 108, TN: 86, FP: 44, FN: 57

**Confusion Matrix (Test Data) - Random Forest:**
TP: 129, TN: 75, FP: 55, FN: 36

## Conclusion

The Random Forest model is the star performer for predicting contraceptive method usage in this project. 🌟 There's always room for improvement though, maybe some hyperparameter tuning or trying out other algorithms could boost performance even more! 💪

