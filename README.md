## Insight-Project
### As a Health Data Science Fellow at Insight Data Science in Boston, I had the opportunity to choose and execute a data science project in four weeks.

I chose to focus on the issue of preterm labor. I developed an app using clinical features to predict whether a pregnant patient should be classified as high or low risk by the treating clinician. 

By training a gradient boosting classifier on the National Children's Study (NCS) and National Pregnancy and Health Survey (NPHS) datasets, I was able to predict the preterm risk class with a recall of 0.51. 
The business value of my project is linked to resource utilization in healthy pregnancies. The American College of Obstetricians and Gynecologists (ACOG) recommends two prenatal ultrasounds (US) in low risk pregnancies, but currently pregnant women in the United States receive 4,5 of them on average. The objective on my app was to help stratify a clinician’s pregnant patient population to high or low risk based on pre-existing and current medical conditions, to better guide and justify the amount of US testing performed to the patients (thus favoring the official guidelines).

My P2 app can be found here: https://preterm-predictor.herokuapp.com/.

#### In this repository, you can find all of the Jupyter notebooks starting from the exploratory data analysis of the NCS datasets (the teaching version is available to download freely at https://ncsarchive.s-3.net/bioshare/teaching_datasets/), to the machine learning models exploration, to the training and validation of LightGBM (chosen model) as well as Logistic regression/Naive Bayes.
For information on the app deployment, please refer to my Insight-App repository.
