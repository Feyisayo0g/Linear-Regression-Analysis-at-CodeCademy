# Linear-Regression-Analysis-at-CodeCademy
Linear Regression Analysis

### Background
This project involves working as a data analyst alongside the Codecademy curriculum team to improve the learner experience. The dataset used in this analysis, though simulated, mirrors the type of data Codecademy might collect to understand factors influencing learner performance on quizzes. The data includes student scores, the number of completed content items, and the lesson taken before the quiz.

### Executive Summary
The goal of this project is to analyze the relationship between quiz scores and various factors such as the number of completed content items and the specific lesson taken before the quiz. By applying linear regression models, we aim to uncover insights that can help Codecademy enhance its educational content and improve learner outcomes. The analysis revealed that both the number of completed content items and the lesson type significantly influence quiz scores.

### Goals of Analysis
- Investigate the relationship between quiz scores and the number of completed content items.
- Examine the impact of the type of lesson taken immediately before the quiz on learner performance.
- Provide actionable insights to the curriculum team to optimize educational strategies and improve learner performance.

### Methodology
- Data Inspection: Load and inspect the dataset to understand its structure and contents.
- Scatter Plot and Linear Regression:
  - Create a scatter plot to visualize the relationship between quiz scores and completed content items.
  - Fit a linear regression model to predict quiz scores based on the number of completed content items.
  - Interpret the slope and intercept of the regression model.
  - Add the regression line to the scatter plot to evaluate the model's fit.
- Prediction and Residual Analysis:
  - Predict quiz scores for a given number of completed items.
  - Calculate fitted values and residuals to check the normality and homoscedasticity assumptions of the linear regression model.
- Lesson Impact Analysis:
  - Create a boxplot to compare quiz scores between different lessons.
  - Fit a linear regression model to predict quiz scores based on the lesson type.
  - Calculate and compare mean quiz scores for each lesson.
- Advanced Visualization:
Use seaborn’s lmplot to visualize the relationship between quiz scores and completed items, colored by lesson type.

## Key Insights
- There is a positive linear relationship between the number of completed content items and quiz scores, with each additional completed item increasing the expected quiz score.
- The residuals of the model are approximately normally distributed, and the homoscedasticity assumption is met, indicating a good fit.
- Learners who took Lesson A scored higher on average than those who took Lesson B, suggesting that Lesson A may better prepare students for the quiz.

### Recommendation
- Encourage learners to complete more content items to improve their quiz performance, as indicated by the positive relationship between completed items and scores.
- Investigate and enhance the content of Lesson B to match the effectiveness of Lesson A in preparing students for quizzes.
- Use the insights gained from this analysis to further refine and optimize the learning experience at Codecademy, potentially incorporating multiple variables in future regression models for deeper analysis.
