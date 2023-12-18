# INTELLIGENT ROAD ACCIDENT SEVERITY PREDICTION
# 1. Introduction
Road accidents are a prevalent and unfortunate occurrence that poses a significant threat to public safety.Every day, countless individuals find themselves involved in unexpected and often tragic collisions on the roads. Numerous things, such as careless driving, speeding, intoxication, bad weather, and mechanical breakdowns, can cause these collisions. Road accidents have far-reaching effects, including serious injury, fatalities, and significant property and vehicle damage. Road accidents are a pressing concern that demands collective efforts to address and mitigate their impact. 

This project tries to predict severity of road accidents based on several parameters such as weather, location, conditions of roads, etc. This proactive approach enables authorities to allocate resources, enhance emergency response, and implement targeted safety measures, aiming to mitigate risks and minimize the impact of accidents. Ultimately, it serves as a critical tool in fostering safer roads by anticipating and addressing the severity of potential accidents, thereby improving overall road safety and emergency management.

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

Accuracy Obtained(in %) : 98.74175234003376

Classification Report : 

![ex_cr](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/505792db-c597-468d-9d5e-88d768bb03ff)
![ex_cm](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/3fd7c95a-b46e-4413-9e19-be251668f18e)

# 3.2. Logistic Regression
Logistic Regression is a foundational principle in statistics and machine learning that plays a crucial role in binary and multi-class classification tasks. Contrary to popular belief, logistic regression is a classification algorithm rather than a regression algorithm. It is used to forecast the likelihood that a specific input instance belongs to a specific class. The result of logistic regression is a probability value that lies between 0 and 1 using the logistic function, also known as the sigmoid function.

Accuracy Obtained(in %) : 85.17338159600201

# 3.3. Random Forest Classifier 
It builds an ensemble of decision trees, where each tree is trained on a different subset of the given dataset. These decision trees work together to make predictions, and based on the majority number of votes the algorithm produces the final result. This model can handle various categories of data and is resistant to overfitting. Though it can provide competitive results, it is important to note that a Random Forest Classifier might not always be an excellent choice due to its incapability to capture complex linguistic nuances in a comprehensive manner.

Accuracy Obtained(in %) : 98.73254564983889

# 3.4. XGBoost Classifier
XGBoost (Extreme Gradient Boosting) is a potent and popular machine learning algorithm that falls under the category of gradient boosting methods. It builds a powerful ensemble model out of the predictions of several smaller models, typically decision trees. The goal of each succeeding model is to fix the mistakes caused by the prior models. XGBoost can be effectively applied to sentiment analysis tasks. While it is not the most popular algorithm for sentiment analysis especially when dedicated models such as LSTM exist, it can still provide competitive results with appropriate feature engineering and parameter tuning.

Accuracy Obtained(in %) : 89.81740064446831

![xg_cr](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/ec1564b8-7b07-43dc-b71d-f54cc3bc4b5d)
![xg_cm](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/75f98337-64c2-4b7a-aa70-dc487c67e2c8)

# 3.5. Decision Tree Classifier
The Decision Tree Classifier is a fundamental supervised learning algorithm used for classification tasks, renowned for its simplicity, interpretability, and effectiveness across various domains. It operates by partitioning the feature space into segments, forming a hierarchical tree-like structure, where each internal node represents a feature and each leaf node represents a class label or outcome. They mimic human decision-making, breaking down complex decision paths into simpler, understandable rules.
Additionally, decision trees are non-parametric, handling both numerical and categorical data without requiring extensive data preprocessing. They can manage missing values and perform well on large datasets, showcasing robustness against outliers.

Accuracy Obtained(in %) : 94.29185207917754

![dt_cr](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/e658a292-14ea-4808-8dfb-a94174492a25)
![dt_cm](https://github.com/ShrutiGoyal9990/Road_Accident_Severity_Prediction_System/assets/121054868/ebe77728-b74d-43d2-8ad9-00d8ec224537)
