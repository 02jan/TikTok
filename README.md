# Classification of TikTok video reports

## Overview
The goal of this project was to build a logistic regression model using verified status to help us understand how video characteristics relate to verified users. The project utilized synthetic data created for this project in partnership with TikTok. The final logistic regression model performed with 66% accuracy and 61% precision when predicting the 'not verified' class.

## Business Understanding
TikTok users have the ability to report videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. This process generates a large number of user reports that are difficult to address quickly. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

## Data Understanding
Synthetic data was created for this project in partnership with TikTok. It consisted of 19382 reports and 11 features. 18142 reports were not verified while 1240 reports were verified.

![image](https://github.com/user-attachments/assets/67f773f9-8e93-46c5-bbc6-31206e25d844)

## Modeling and Evaluation
A logistic regression model with 7 features was used to determine which feature is more important to predict whether a report is verified or not. The below plot shows that video_duration_sec was the most assosiated with higher odds of the user being verified. The overall model performed with 66% accuracy and 61% precision.

![image](https://github.com/user-attachments/assets/4fbe8f4a-7ad4-42bd-a97d-025332aba941)

## Conclusion
This model can benefit the moderators by reducing their backlog of user reports and prioritize them more efficiently. A parametric model will be able to better determine how much each variable will influence the actual verifification status of the reports. Adding more information on users' past reports in the future will also help stakeholders address their business problem better.
