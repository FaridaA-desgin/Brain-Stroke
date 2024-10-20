# Brain Stroke

# Abstract
When the brain is deprived of blood and the oxygen it contains, or when bleeding inundated surrounding tissue, it causes the brain to swell, which can cause a stroke. Both incidents, among other things, can result in long-term vision problems, seizures, fatigue, loss of speech, memory loss, and paralysis. They can also be fatal if severe enough. Anyone, from children to adults, can have a stroke, but some people are at a higher risk than others. Strokes are more common as people get older. The purpose of this study is to help diagnose the different causes of a brain stroke using factors such as gender, age, hypertension, heart disease, work type, residence type, average glucose level, BMI, and smoking status to predict whether a person will have a stroke or not. The machine learning techniques that will be used are Logistic Regression, k-Nearest Neighbor(kNN), Support Vector Machines(SVM), Random Forest, Decision Trees, Extreme Gradient Boosting (XGBoost), and Naive Bayes. 

# Introduction
A brain stroke can happen to anybody who has high blood pressure, high cholesterol, heart disease, diabetes, or high blood sugar. The same goes for those who are overweight, smoke, drink a lot, or are physically sedentary. Males are more likely to get a stroke than females, and the risk of stroke rises with age. High blood pressure (hypertension), high cholesterol (hyperlipidemia), Type 2 diabetes, as well as those who have a history of stroke, heart attack, or abnormal heart rhythms such as atrial fibrillation, are other medical disorders that raise the risk of stroke (Centers for Disease Control and Prevention, 2022). A brain stroke can cause many long-lasting issues that may cause long-term disability, lasting brain damage, or death. Knowing whether a patient is prone to having a stroke could help doctors prevent long-lasting brain damage and save more patients. 

Studies such as the one done by Bandi et al. (2020) were created to improve and predict brain stroke machine learning. The study done by Bandi et al. (2020) was done to help predict brain stroke severity. This study was not just done to predict stroke severity but also to address past studies' limitations. Bandi et al. (2020) and many other studies conducted research in order to enhance and forecast brain stroke in machine learning. The research was conducted to assist in predicting the severity of a brain stroke. This study was conducted not only to predict stroke severity but also to address the shortcomings of previous studies. The models that were used were logistic regression, linear regression, random forest, decision tree, adaptive boosting, k-means, and naive Bayes. Studies like these create new insight for future research improvement on predicting brain stroke. 

Based on previous research, the goal of this study is not only to forecast if a patient will have a brain stroke but also to determine what factors are more likely to trigger a brain stroke. For example, BMI, one of the predictor variables, can be classified as a high cause of patient four’s brain stroke. This study will help with understanding if each patient has a different variable that is more prone to cause their brain stroke or if the individual patients don’t matter and the variable is the same for everyone. The data that will be used is from the UCI open-source data warehouse which consists of 11 variables and 4982 documents. The variables consist of the variables; gender, age, hypertension, heart disease, work type, avg glucose level, BMI, smoking status, and stroke. Stroke is the decision variable.

# Related Work
Since brain strokes affect the central nervous system, strokes have become one of the main causes of death in recent years. Ischemic and hemorrhagic strokes cause the most significant damage to the central nervous system. The research study mentioned above by (Bandi et al. 2020) addresses the limitation of existing research by using an improvised random forest for a stroke prediction algorithm that analyzes the levels of risks obtained within the strokes. The data set used for this study consists of 3,123 men and 1,676 women which make up the 4,799 participants. The results revealed that the improvised Random Forest ensemble technique combined with a stroke prediction algorithm is used in this study to determine the risk factor. The stroke predictor model has an accuracy of 96.97% and an error rate of 0.03%.

Sirsat et. al. (2020) used machine learning techniques to classify brain stroke into 4 categories based on their functionalities or similarity, and then review studies of each category systematically. The researchers found a gap in brain stroke studies in which there aren’t enough stroke treatments. This study’s main focus is to do a detailed review of the application of machine learning for brain stroke. Their methodology consists of using eight research questions that are used to analyze each study. Their methodology entails the use of eight research questions to examine each study. Such as “What machine learning or deep learning technique was used?” and “Which features were used?” All studies were grouped into 4 categories: stroke prevention, stroke diagnosis, stroke treatment, and stroke prognostication/outcome prediction. The study resulted in the findings of 8 studies about stroke prevention, 18 studies on stroke diagnosis, 4 studies about stroke treatment, and 9 studies about stroke prognostication. 

The machine learning techniques for brain stroke prognostic or outcome prediction are Artificial Neural Networks, Support Vector Machines, Residual Neural Networks, Structured Receptive Fields, Random Forest, Gaussian Process model Regression, and Logistic Regression. The machine learning techniques for brain stroke treatment are Perceptron Learning Algorithm, K-Center with Radial Basis Functions, Quadratic discriminant analysis, Linear discriminant analysis, Naive Bayes, Random Forest, artificial neural network, Extreme Learning Machine, K-Nearest Neighbors and Linear Support Vector Machine. The machine learning techniques for brain stroke Diagnosis are Convolutional Neural Networks, Artificial Neural Networks, Random Forest, Bayesian Classifier, Multilayer Perceptron, k-Nearest Neighbor, and Support Vector Machines.  Sirsat et. al. (2020) research is great for understanding the different types of machine learning models past researchers have used for different brain stroke prediction types. This study is also ideal for future research and finding gaps that relate to machine learning of brain stroke. 

Dritsas & Trigka (2022) used machine learning to develop and evaluate several models to design a robust framework for the long-term risk prediction of stroke occurrence. This study utilizes the identical dataset that will be employed. Evaluating past research with the same dataset will allow us to have an understanding of what to expect, what to improve, and focus on. The machine learning models that were used are Naive Bayes, Random Forest, Logistic Regression, K-Nearest Neighbors, Stochastic Gradient Descent, Decision Tree, Multilayer Perceptron, Stacking, and Majority Voting. Accuracy, F-measure, and Area under the Curve were utilized as performance evaluation metrics. In terms of the stroke class, the metrics demonstrated the models' validity and propensity for prediction. With an AUC of 98.9%, an F-measure of 97.4%, and an accuracy of 98%, the stacking classification model performs better than the other techniques. The stacking method is an effective strategy for identifying people who are at a high risk of having a stroke over the long term, according to the study's findings.

# Methods
Logistic regression is one of the methods that will be used. A logistic regression model is a statistical model that is used to study the connection between a binary dependent variable or outcome variable and one or more independent variables (Shmueli et. al., 2016). Given the values of the independent variables, the purpose of logistic regression is to determine the likelihood of the dependent variable assuming a specific value (typically 0 or 1). 

A decision tree is a form of prediction model used in machine learning and data mining. It resembles a tree, with each node representing a choice and each leaf node representing an expected consequence. Both classification and regression issues may be solved using decision trees. The decision tree algorithm partitions the data recursively based on the values of the independent variables (Kingsford et al. 2008). This method finds the variable that best divides the data into distinct classes or causes the largest decrease in variance for the dependent variable at each node of the tree. This variable becomes the node's splitting criteria. Based on the value of the splitting criterion, the data is then divided into two or more branches. This method is repeated until a stopping condition, such as reaching a maximum depth or having a certain amount of observations in a leaf node, is fulfilled (Kingsford et al. 2008). Overall, decision trees are a robust and adaptable predictive modeling technique with a wide variety of applications. Nevertheless, caution must be exercised in order to avoid overfitting and ensure that the model is accurate and resilient.

Naive Bayes is a probabilistic classification method built on the theory of Bayes. It is referred to as "naive" because it assumes that all characteristics (or variables) are independent of one another. Despite this simplifying premise, Naive Bayes can still be very successful in a wide range of uses. The program begins by creating a probabilistic model of the various groups based on the training data. The chance distribution of each characteristic for each class is estimated using this model. Once constructed, the model can be used to forecast the class of new, previously unseen data points based on their feature values.

The random forest algorithm is a bagging method extension that employs both bagging and feature randomness to produce an uncorrelated forest of decision trees. Feature randomization, also known as feature bagging, provides a random subset of features, ensuring low correlation among decision trees Schonlau & Zou (2020). This is a significant distinction between decision trees and random forests. Random forests select only a subset of the available feature splits, whereas decision trees consider all of them.

The prediction determination will differ depending on the type of problem. Individual decision trees will be averaged for a regression task, and a majority vote on the most common categorical variable will produce the projected class for a classification challenge Schonlau & Zou (2020). One significant disadvantage of employing random forests is that it takes time. Because random forest algorithms can handle massive data sets, they can produce more accurate predictions. But, because they compute data for each individual decision tree, they can be slow to process data.

Boosting is an ensemble learning approach for constructing a strong classifier from a sequence of weak classifiers. In dealing with bias-variance trade-offs, boosting algorithms are critical. According to Ma et al. (2020), Extreme Gradient Boosting Decision Tree (XGBoost) is an iterative decision tree algorithm that consists of multiple decision trees. The algorithm employs a parallelized implementation, which enhances the process of sequential tree building. XGBoost is a highly efficient GBDT algorithm that combines software and hardware optimization techniques to yield superior results while using fewer computing resources than other methods. The algorithm uses the "max_depth" parameter first to specify the maximum depth of the trees and then begins to prune the trees backward, using a depth-first approach that significantly improves its computational performance.

# Dataset
To get the dataset prepaid for model implication it was cleaned to make sure it has no missing values and dropped the variable “work_type”. Considering the values of the column which are children (stay-at-home parent), government job, private, never worked and self-employed this variable does not have enough information. There are quite a variety of jobs related to being self-employed or having a government job. Government jobs can go from being a nurse or tax specialist to a firefighter or police officer. The working conditions are all too different to be simply classified into 5 values to be used in predicting brain stroke. Studies have shown that in fact, the job does not have a significant association with stroke. 

Zhang et. al. (2019) examine the external and internal risk factors of stroke prevention. The study discovered that those who worked 55 hours or more per week had a greater risk of incident stroke than those who worked ordinary hours (35-40 hours per week). Long working hours might generate chronic stress and indirectly increase exposure to stroke risk factors. Working long hours was linked to physical inactivity, increased alcohol intake, and an increased risk of smoking. Although the relationship between long working hours and stroke is influenced by numerous factors, including the work environment and individual characteristics, long working hours were concluded to be a significant enough risk to be avoided. Schiöler et al. (2015) did a cohort study and found no significant associations between the psychosocial work environment, as measured by the job demand-control model, and ischaemic stroke. The study was based on over 75,000 male construction workers and construction work is known as a physically demanding profession. 

After removing the mentioned variables, the needed variables in the dataset were changed into binary factors. “Gender” for example was changed from male to 1 and female to 0. The same goes for the variables ``residence_type” and “smoking_status”. The data was then checked to see if it is unbalanced. After doing a value count of the decision variable, the output showed that the majority of the observations (4733 out of 4981) did not have a brain stroke, while a small minority of observations (248 out of 4981) have had a stroke. To deal with this the data will be oversampled and undersampled. 

Oversampling and undersampling are machine learning techniques used to correct class imbalances in datasets. Oversampling is the process of increasing the number of cases of a minority class in a dataset. This may be accomplished by reproducing samples from the minority class at random. Undersampling is the practice of reducing the instances of the majority class of a dataset. This can be accomplished by deleting instances from the majority class at random, or by picking a subset of instances from the majority class that is comparable in size to the minority class. For each model, the undersampled, oversampled, and original datasets will be used.  

# Performance Metrics
The performance metrics that will be used to evaluate the models’ performance are the confusion matrix, precision, recall, F1-score, AU-ROC, and the models' accuracy percentage. These metrics are commonly used for evaluating classification models. Hossin et. al. (2015) analyzes the critical role that evaluation metrics play in achieving a well-trained model. The research shows that accuracy has limitations and shouldn’t be the only performance metric used. One of the main limitations the research covers is it produces less distinctive and less discriminable values. As a result, the discriminating ability to accuracy in selecting and determining the ideal classifier is reduced. The dataset will be split into 60% for training and 40% for validation when preparing the models. 

# Results

# Original Data
When using the original dataset without balancing the classes, the models shown in Table 1 did not perform well. It was expected that models would have poor performance with an unbalanced dataset. However, based on the performance metrics that received a percentage of over 80%, AU-ROC, and Accuracy would be the best metrics for evaluating which model performed well with unbalanced data. It is important to note that the performance metrics only show how well the models predicted a patient not having a brain stroke. This is because the original dataset has 95% of patients without a brain stroke and only 5% with a brain stroke. Based on the highest accuracy and AUROC scores, the Logistic Regression (LogR) model appears to be the best-performing model. According to the unbalanced data, the Naive Bayes model has the highest number of actual positives (309) and the lowest number of predicted negatives (66) based on the confusion metrics presented in Table 1a. These metrics will provide insight into how well the models perform once applied to the oversampled and undersampled data.

Table 1: Original Dataset Performance Metrics
![Table 1](https://github.com/user-attachments/assets/69412baf-6146-48d0-8ef2-1c6f92c59d03)

Table 1a: Original Dataset Confusion Metrics
![Table 1a](https://github.com/user-attachments/assets/32284e52-f959-4dc7-8140-c1a4124ca08f)

To evaluate the most important features of predicting each patient's cause of a brain stroke, the Decision Tree was run with feature importances. Table 1b shows the most important variable for a random selection of 10 patients. These patients all seem to have gender as the most important variable that contributes to brain stroke. 

Table 1b: Original Data Feature Importances
![Table 1b](https://github.com/user-attachments/assets/93f782ef-52a1-47a0-869b-a53ec2f171bb)

Looking at the dataset overall the most impactful feature is variable 2, “age”, with a score of 0.7658. The variables 7-9 are “avg_glucose_level”, “BMI”, and “smoking_status” which have a very low score that does not have a large impact on brain stroke but should be taken into account. Since the original data, under-sampled and over-sampled data have different numbers of observations, it is important to run feature importance separately for each case, as the results may vary.

Table 1c: Original Data Feature Importance Score
![Table 1c](https://github.com/user-attachments/assets/b07c5cc3-e327-470b-b1ab-13edd26258ba)

# Under-Sampled
After running models with under-sampling the results of their performance metrics were good. Table 2  is the under-sampled models based on all metrics. The XGBoost model has an F-score (87%), precision (79%), and recall (97%), which suggests that it is better at correctly identifying positive cases, while still maintaining a relatively low rate of false positives. It also has high accuracy (86%) and AUROC (0.97), indicating good overall performance. 

For predicting brain stroke, a model with high recall as it is more important to correctly identify as many positive cases (i.e., cases where the patient had a brain stroke) as possible, even at the cost of a higher false positive rate. Therefore, based on the performance metrics, the Random Forest model has high accuracy (87%), F-score (89%), Precision (80%), and AU-ROC (96%), indicating that it performs well overall. It also has a very high recall (1.0), meaning that it is able to identify all positive cases correctly.  Looking at the confusion matrices, Table 2a, Gradient Boost (XGBoost) model predicted the most correct actual positives and actual negatives. The model only predicted 2 false negatives and 2 false positives. 

Table 2: Under-Sampled Model Performance Metric 
![Table 2](https://github.com/user-attachments/assets/282484ee-e457-43c3-b803-ef2e777eb1d9)

Table 2a: Under-Sampled Model Confusion Matrix
![Table 2a](https://github.com/user-attachments/assets/23de939b-2a60-402c-9098-1abdee97105c)

Table 2b, shows the most important variable for a random selection of 10 patients. Under the under-sampled data, the most important feature for patient 457 is “gender”, while for patient 231 the variable “age”. Looking at Table 2c the overall under-sampled dataset the most impactful feature is variable 2, “age”, with a score of 0.9327. Variable 7, “BMI”, has a very low score that does not have a large impact on brain stroke but should be taken into account.

Table 2b: Under-sampled Data Feature Importances
![Table 2b](https://github.com/user-attachments/assets/15eb5ef1-24b3-4268-b589-4b95aca9c320)

Table 2c: Under-sampled Data Feature Importance Scores
![Table 2c](https://github.com/user-attachments/assets/bd87d098-bbf6-4388-8fcf-c841e91bebeb)

# Over-Sampling 
Additionally, the Random Forest (RandomF) model achieved a perfect score of 1.0 for all performance metrics, indicating a perfect ranking of positive and negative classes. However, this may also suggest an overfitting model. Ideally, a performance metric percentage between 90-75% is desired to evaluate whether the models are performing well and learning. Based on this understanding, the RandomF model may not be the best-performing model.

In Table 3 and Table 3a, the models are trained using oversampled data. The XGBoost model achieved the highest overall performance score. The model's F-score (94%), precision (89%), and recall (99%) show that it correctly identified positive cases while maintaining a low rate of false positives. It also demonstrated high accuracy (93%) and AUROC (94%), indicating good overall performance. The XGBoost model identified 2533 true positives, which are cases where the model predicted a positive outcome. The model also predicted 3147 negatives, when the dataset only had 2821 true negatives. Therefore, the model predicted 326 positives and 326 negative cases under the XGBoost model. The second-best model would be the Decision Tree with the second-best confusion matrix and performance metrics.

Table 3: Over-Sampled Model Performance Metric
![Table 3](https://github.com/user-attachments/assets/6cc71e7e-be73-49f5-b78e-9bddec716a43)

Table 3a: Over-Sampled Model Confusion Metrics
![Table 3a](https://github.com/user-attachments/assets/637beafb-f0c2-479c-bc43-d45b568ccb43)

Most significant variable for over-sampled data of 10 patients. Analysis shows that “age” (Variable 2) is the most important variable contributing to brain stroke in the majority of patients, while gender has a lower impact, being the most important variable for only 4 patients. “Hypertension” (Variable 3) and “avg_glucose_level” (Variable 7) have lower scores and less impact on brain stroke, but they should still be taken into account.

Table 3b: Under-sampled Data Feature Importances
<img width="217" alt="Table 3b" src="https://github.com/user-attachments/assets/d9d6663a-0e31-4a25-8a70-eebaa8c502fe">

Table 3c: Over-sampled data Feature Importance
![Table 3c](https://github.com/user-attachments/assets/5e5d7ce6-fbad-415a-972f-a97bcc0d3274)

# Conclusions
A brain stroke can occur in individuals with high blood pressure, high cholesterol, heart disease, diabetes, high blood sugar, overweight, smoking habits, excessive drinking, or physical inactivity. Males and older individuals are more likely to suffer from a stroke. A stroke can result in severe long-lasting effects, including brain damage, disability, or even death. Therefore, identifying patients prone to stroke can help doctors prevent long-term brain damage and save more lives. Based on the dataset, models used and the results found that the under-sampled and over-sampled model of Extreme Gradient Boosting Decision Tree (XGBoost) is the best model for predicting brain stroke. The aim of this study was to not just predict stroke but also to determine the risk factors that are more likely to trigger a brain stroke. Based on the feature importance performed the variables “age” & “gender” have the most impact on predicting brain stroke. The continuation of this study would include getting a more detailed dataset with variables such as diabetes, heart disease, and other stroke risk factors to better assist in identifying patients prone to a brain stroke. 

# References 
Bajaj, A. (2023, February 17). Performance metrics in machine learning [complete 
guide]. neptune.ai. Retrieved March 20, 2023, from https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide

Bandi, Vamsi, Debnath Bhattacharyya, and Divya Midhunchakkravarthy. "Prediction of 
Brain Stroke Severity Using Machine Learning." Rev. d'Intelligence Artif. 34.6 (2020): 753-761.

Centers for Disease Control and Prevention. (2022, November 2). About stroke. 
Retrieved March 8, 2023, from https://www.cdc.gov/stroke/about.htm#:~:text=A%20stroke%2C%20sometimes%20called%20a,term%20disability%2C%20or%20even%20death.

Dritsas Elias, and Maria Trigka. "Stroke risk prediction with machine learning 
techniques." Sensors 22.13 (2022): 4670.

Hossin, M., & Sulaiman, M. N. (2015). A review on evaluation metrics for data 
classification evaluations. International journal of data mining & knowledge management process, 5(2)

Kingsford, C., & Salzberg, S. L. (2008). What are decision trees?. Nature Biotechnology, 
26(9), 1011-1013.

Liu S., Mcgree J., Ge Z., Xie Y. (2016). Computational and statistical methods 
for analyzing big data with applications. Academic Press.

Ma, J., Yu, Z., Qu, Y., Xu, J., & Cao, Y. (2020). Application of the XGBoost machine 
learning method in PM2. 5 Prediction: A case study of Shanghai. Aerosol and Air Quality Research, 20(1), 128-138.

Schiöler, L., Söderberg, M., Rosengren, A., Järvholm, B., &amp; Torén, K. (2015). 
Psychosocial work environment and risk of ischemic stroke and coronary heart disease: A prospective longitudinal study of 75 236 construction workers. Scandinavian Journal of Work, Environment &amp; Health, 41(3), 280–287. https://doi.org/10.5271/sjweh.3491

