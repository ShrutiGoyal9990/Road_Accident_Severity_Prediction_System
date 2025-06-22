# INTELLIGENT ROAD ACCIDENT SEVERITY PREDICTION
# 1. Introduction
Road accidents are a prevalent and unfortunate occurrence that poses a significant threat to public safety. Every day, countless individuals find themselves involved in unexpected and often tragic collisions on the roads. Road accidents have far-reaching effects, including serious injury, fatalities, and significant property and vehicle damage. Road accidents are a pressing concern that demands collective efforts to address and mitigate their impact. 

The main goal of this research is to identify how different features such as the type of roads, weather patterns, and vehicle speed contribute to road accidents. Understanding these factors can help lower the probability of accidents and enable preventative measures. This study compares the performance of five ML (Machine Learning) models: Extra Trees Classifier, Logistic Regression, Random Forest Algorithm, XGBoost, and Decision Tree Classifier. The Extra Trees Classifier, known for its high ac
curacy and robustness, stands out in the study. By analyzing most significant features, these models help predict the severity of accidents that cause traffic accidents and enable early intervention and improvement of the system.

# 2. About the Dataset
DATASET LINK : https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset/data

The UK government amassed traffic data from 2000 and 2018, recording 33 features covering over a 1.8 million accidents in the process and making this one of the most comprehensive traffic data sets out there. It's a huge picture of a country undergoing change. 
This dataset consists of various features like, 
Accidental / Longitude: Location of Accident

Accident_Severity: Accident Severity on the Scale of 1 to 5

Number_of_Vehicles: Number of Vehicles Involved

Number_of_Casualties: Number of Casualties in Accident

Light_Conditions: Lighting Condition on the day of Accident

Weather_Conditions: Weather Conditions on the day of the Accident

Road_Surface_Conditions: Road Surface Conditions of Accidental Spot

Year: Year of Accidental Event

Police_force: No. of police force

Number_of_vehicles: No. of Vehicles involved in Accident

# 3. Algorithms Used
# 3.1. ExtraClassClassifier
The ExtraTreesClassifier (Extremely Randomized Trees) ensemble learning methods in machine learning, stands out for its effectiveness in handling diverse datasets. It operates similarly to the Random Forest algorithm, constructing multiple decision trees. However, what distinguishes ExtraTrees is its additional level of randomness during the tree-building process. It selects thresholds for best feature splits. This deliberate randomness aids in creating a more diverse set of trees and reduces the risk of overfitting, making it particularly robust in handling noisy or high-dimensional data.

ExtraTreesClassifier requires less computational resources and reduced hyperparameter tuning compared to some other ensemble methods.

Accuracy Obtained(in %) : 97.74

# 3.2. Logistic Regression
Logistic Regression is a foundational principle in statistics and machine learning that plays a crucial role in binary and multi-class classification tasks. Contrary to popular belief, logistic regression is a classification algorithm rather than a regression algorithm. It is used to forecast the likelihood that a specific input instance belongs to a specific class. The result of logistic regression is a probability value that lies between 0 and 1 using the logistic function, also known as the sigmoid function.

Accuracy Obtained(in %) : 93.72

# 3.3. Random Forest Classifier 
It builds an ensemble of decision trees, where each tree is trained on a different subset of the given dataset. These decision trees work together to make predictions, and based on the majority number of votes the algorithm produces the final result. This model can handle various categories of data and is resistant to overfitting. Though it can provide competitive results, it is important to note that a Random Forest Classifier might not always be an excellent choice due to its incapability to capture complex linguistic nuances in a comprehensive manner.

Accuracy Obtained(in %) : 97.61

# 3.4. XGBoost Classifier
XGBoost (Extreme Gradient Boosting) is a potent and popular machine learning algorithm that falls under the category of gradient boosting methods. It builds a powerful ensemble model out of the predictions of several smaller models, typically decision trees. The goal of each succeeding model is to fix the mistakes caused by the prior models. XGBoost can be effectively applied to sentiment analysis tasks. While it is not the most popular algorithm for sentiment analysis especially when dedicated models such as LSTM exist, it can still provide competitive results with appropriate feature engineering and parameter tuning.

Accuracy Obtained(in %) : 95.12

# 3.5. Decision Tree Classifier
The Decision Tree Classifier is a fundamental supervised learning algorithm used for classification tasks, renowned for its simplicity, interpretability, and effectiveness across various domains. It operates by partitioning the feature space into segments, forming a hierarchical tree-like structure, where each internal node represents a feature and each leaf node represents a class label or outcome. They mimic human decision-making, breaking down complex decision paths into simpler, understandable rules.
Additionally, decision trees are non-parametric, handling both numerical and categorical data without requiring extensive data preprocessing. They can manage missing values and perform well on large datasets, showcasing robustness against outliers.

Accuracy Obtained(in %) : 95.88

# 4. Comparison of Algorithms used
The following figure shows the accuracies of all the models used.

![WhatsApp Image 2025-06-22 at 13 37 02_0f5a8daa](https://github.com/user-attachments/assets/c9e5d8ce-1925-4a9b-bb8e-03fa418596c8)


# 5. Conclusion
This project effectively forecasts road accident severity, empowering authorities to enact safety protocols. Employing five models—ExtraTreesClassifier, Logistic Regression, Random Forest Classifier, XGBoost and Decision Tree Classifier—the ExtraTreesClassifier emerges as the optimal model, boasting a remarkable accuracy of 97.75%. This standout accuracy establishes it as the most fitting model, consolidating its role in accurately predicting accident severity. The analysis revealed that weather conditions had a considerable impact on traffic accidents severity. The algorithms we used consistently identified precipitation, fog, and slippery road conditions as important predictors of accident severity. It also emphasizes the importance of geographic location in determining accident outcomes. Accidents in metropolitan locations, or near crossings were consistently more severe.


