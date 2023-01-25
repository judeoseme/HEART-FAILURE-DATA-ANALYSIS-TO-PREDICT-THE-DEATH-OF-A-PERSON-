# HEART-FAILURE-DATA-ANALYSIS-TO-PREDICT-THE-DEATH-OF-A-PERSON-

HEART FAILURE DATA ANALYSIS TO PREDICT THE DEATH OF A PERSON

Introduction:
The human heart is a vital organ of the body that is responsible for pumping blood around the body through the circulatory system. It supplies the tissues with oxygen and nutrients thereby eliminating waste not needed in the body as well as carbon dioxide.  Cardiovascular disease known as CVD is a disorder that have a huge implication on the heart. They include heart attacks, strokes, and heart failure (Chicco & Jurman, 2020).  The inability of the human heart to pump blood through the circulatory system will result to heart failure. Over the years, heart failure has been an issue of concern for the public affecting millions of people all over the world. According to a recent survey conducted by the World Health Organisation (WHO), about 17.9 million deaths worldwide resulted from CVD, accounting for 31% of all deaths (World Health Organisation, 2021). Nowadays, people are so committed to their place of work with little or no time to rest. Also, the consumption of too many fatty foods such as pizza, burgers etc has contributed to the failure of the heart. To predict the death of a person with heart failure is quite a complex task that involves so many factors. It requires thorough analysis of a variety of variables.  These include analyzing the medical history, current health status, age, gender. Other factors could include their diet as well as their physical activity. To do this it is necessary you have all this data collected on those variables listed above.  However, using machine learning algorithm like Apriori can be used to make predictions about a person’s likelihood of survival. 

Dataset:
The dataset used in this study was obtained from https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records. A total number of 299 medical record of patient (people with heart failure) were used in this study for the analysis along with 13 clinical features. Each patient was tested with the 13 clinical features. These features were later used to develop model to predict the death of a patient with heart failure problem. The following are the features that was used in this study to predict the death of a patient.
1.	Age
2.	Anaemia
3.	Creatinine Phosphokinase
4.	Diabetes
5.	Ejection Fraction
6.	High Blood Pressure
7.	Platelets
8.	Serum Creatinine
9.	Serum Sodium
10.	Sex
11.	Smoking
12.	Time
13.	Death Event 

one can clearly observed that the dataset is grouped into two variables. Categorical and numerical variables. Numerical variables are variables where the measurement or number has a numerical meaning They are strictly values. For example, heart rate measurement is a numerical variable. Comparing this to the above dataset, the numerical variable is listed below.
1.	Age
2.	Anaemia
3.	Creatinine phosphokinase
4.	Ejection fraction
5.	Platelets
6.	Serum creatinine
7.	Serum sodium
8.	Time
A categorical variable is a discrete variable by placing observation into fixed group. Here, everyone can only fix into one group. Using this simple definition, the categorical variable is listed below
1.	Diabetes
2.	High blood pressure
3.	Sex
4.	Smoking
5.	Death event

Explanation and Preparation of dataset:

Data preparation is a fundamental stage of analysing data. It is the process of arranging and manipulating unstructured data prior to the analysis into a more useful form for further analysis or processing. This data processing is very important because it guarantees data integrity, which contributes to reliable observations. A well-informed driven dataset will always be very critical in decision making. In this study, 13 clinical features were used along with a medical record of 299 patient with heart failure. Data preparation is a fundamental stage of data analysis. While a lot of low-quality information is available in various data sources and on the Web, many organizations or companies are interested in how to transform the data into cleaned forms which can be used for high-proﬁt purposes. This goal generates an urgent need for data analysis aimed at cleaning the raw data. In this paper, we ﬁrst show the importance of data preparation in data analysis, then introduce some research achievements in the area of data preparation.

1.	Age:  This is the actual age of the patient
2.	Anaemia: Here we will determine for the presence of low haemoglobin
3.	Creatinine phosphokinase: This is also known as CPK. It is an enzyme found in the brain and skeletal tissues. When the muscle tissue is damaged, it leaks into the blood and excess of it indicates an injury to the heart.
4.	Diabetes: Diabetes is a lifelong condition that causes the blood sugar level of a person to become too high.
5.	Ejection fraction: This is one of many test that can be used to determine how your heart works. It is the measurement of percentage of blood leaving the body each time it contracts.
6.	High blood pressure: This is also known as hypertension. When the blood pressure is consistently too high, it means that the heart must work harder to pump blood for circulation into the body system. So, we will determine if it is high or low.
7.	Platelets: When the level of platelets count is too high, it could form blood clots in the blood vessel.  On the opposite, if it is too low, it could lead to an internal bleeding. So, we will determine the count of platelets.
8.	Serum creatinine: This is a blood test that measures how well the kidney works.  
9.	Serum sodium: This is a test to determine the level of sodium present in the body
10.	 Sex: This basically refer to the gender. Biologically, men have a higher tendency to be diagnosed with heart failure than women since women survive longer.
11.	 Smoking: We will have to enquire if the patients smokes or not.
12.	 Time
13.	 Death event: if the patient will survive it or not

There are no null or missing values in the dataset.

A brief discussion of the algorithm used:
Association rule mining is unsupervised learning where algorithm tries to learn without a teacher as data are not labelled. It is a technique used in data mining to discover relationships between variables hidden in large dataset. Association rules are not descriptive method. Rather they are predictive method generally used to make predictions about future events. They are used to identify new trends between objects in a set.  For instance, if a dataset contains information about the items that customers purchased at a store, association rule mining can be used to identify items that were frequently purchased together. There are several algorithms that can used for association mining.  Apriori Algorithm is one of the algorithm used in association rule mining and it is used in a situation where we want to find the patterns among qualitative items so using Apriori here will not be beneficial as far as this dataset is concerned. In this study, I applied the logistic regression. The logistic regression is a supervised machine learning algorithm that can be used to model the probability of a certain event. In logistic regression, the dependent variable is a binary variable that takes on a value of 0 and 1 indicating the presence or absence of an event happening. In a nutshell, the logistic regression is used for binary classification to predict the output variable that is discrete in two classes.

The application of data-mining techniques to selected datasets that you choose using Python
Data mining technique is a method of collecting data from different available sources and arranging it yield a more valuable insight. It involves an examination of raw and pre-existing data to gain more useful information. In this study, my dataset contains some significant pattern and useful information. I was able to check for the death sample for which death could happen.


Conclusions:

1.	The distribution of the data is not equally distributed, but the model performs with 86% accuracy
2.	The model performs well in case all the features in this dataset are considered.





Ethical / legal Consideration

The dataset used for this study only considered 299 medical records of patient with heart failure. It is important to note that the number is quite small to analyse considering the number of people with heart failure. Therefore, it is necessary that analysing large volume of data will modify the result
Predictive factors such as age, ejection fraction, platelets, are the most determinant factors but could change if a large amount of data is analysed.

 References
Chicco, D. and Jurman, G. (2020) Machine Learning Can Predict Survival of Patients with Heart Failure from Serum Creatinine and Ejection Fraction Alone. BMC Medical Informatics and Decision Making, 20, Article No. 16.
















