Ola Cabs Churn Predictions:

In this project, I focused on understanding and predicting driver churn at Ola, a leading ride-hailing company. The goal was to identify key drivers of churn, develop predictive models, and provide actionable recommendations to improve driver retention and overall workforce stability.

Problem Definition:

Industry Challenge: High driver turnover disrupts operations, impacts morale, and increases recruitment costs.
Business Impact: Addressing churn is crucial for growth and efficiency, as retaining drivers is less costly than recruiting and training new ones.
Objective: Develop predictive models to determine the likelihood of a driver leaving the company based on various attributes.

Key Insights:

Gender-Based Churn: 39.73% of males have left the job compared to 28.14% of females, indicating higher churn among males.
Education Level: Churn rates are consistent across education levels, with a slight increase for those with Education Level 2.
Designation: Drivers at Designation 1 show the highest churn rate, followed by those at Designation 2.
Grade: Half of the drivers in grades 1 and 2 have churned.
Quarterly Rating: A last quarterly rating of 1 correlates with a 60% churn rate, highlighting the impact of performance ratings.
Income Increase: 67.74% of drivers without an income increase have churned, marking it as a critical factor in retention.

Model Performance:

Model 1 (Random Forest Classifier):
F1 Score: 87%
Accuracy: 82%
AUC Score: 86%
Effectively discriminates between churned and not churned employees with robust predictability.

Model 2 (Gradient Boosting Classifier):

F1 Score: 88%
Accuracy: 83%
AUC Score: 88%
Shows superior performance over Model 1, offering a more refined understanding of feature impacts.

Most Influential Features:
Both models identified the following as key predictors of churn:
1.Income Increase
2.Quarterly Rating Increase
3.Driver's Grade
4.Education Level

Recommendations:

Gender-Specific Initiatives: Develop targeted retention programs for male drivers, focusing on career development, competitive pay, and work-life balance.
Education Level Focus: Provide additional training for employees with Education Level 2 to align their roles with their skills.
Designation-Specific Strategies: Enhance job satisfaction for Drivers at Designation 1 and 2 through role improvements and recognition.
Grade-Related Adjustments: Improve support for drivers in grades 1 and 2 with better onboarding and mentorship programs.
Performance Evaluation: Revamp performance evaluations to provide fair feedback and support for low performers.
Development Programs: Implement continuous improvement programs focused on personal development and recognition.
Compensation Review: Restructure salary increments and bonuses to be performance-based and transparent.

Additional Considerations:

Implement Retention Strategies: Identify at-risk drivers early to offer incentives or support.
Optimize Recruitment: Focus on profiles with lower predicted churn.
Improve Driver Experience: Address systemic issues to enhance satisfaction and reduce churn
