# parasite-predictions-ml
# The Smith Parasite

Link for Kaggle: https://www.kaggle.com/competitions/the-smith-parasite

## 1. Introduction
A new disease has recently been discovered by Dr. Smith, in England. You have been brought in to investigate. The disease has already affected more than 5000 people, with no apparent connection between them.
The most common symptoms include fever and tiredness, but some infected people are asymptomatic. Regardless, this virus is being associated with post-disease conditions such as loss of speech, confusion, chest pain and shortness of breath.
The conditions of the transmission of the disease are still unknown and there are no certainties of what leads a patient to suffer or not from it. Nonetheless, some groups of people seem more prone to be infected by the parasite than others.


## 2. Objective of the project
In this challenge, your goal is to build a predictive model that answers the question, “Who are the people more likely to suffer from the Smith Parasite?”. With that goal, you can access a small quantity of sociodemographic, health, and behavioral information obtained from the patients.
As data scientists, your team is asked to analyze and transform the data available as needed and apply different models to answer the defined question in a more accurate way. Can you build a model that can predict if a patient will suffer, or not, from the Smith Disease?
The score of your predictions is the percentage of instances you correctly predict, using the f1 score.


## 3. Datasets
You have access to two different datasets:
  1. The training set should be used to build your machine learning models. In this set, you also have the ground truth associated to each patient, i.e., if the patient has the disease (Disease = 1) or not (Disease = 0). Is composed by: train demo.csv - the training set for demographic data and the target, train health.csv - the training set for health related data, train habits.csv - the training set for habits related data.
  2. The test set should be used to see how well your model performs on unseen data. In this set you don’t have access to the ground truth, and the goal of your team is to predict that value (0 or 1) by using the model you created using the training set. Is composed by: test demo.csv - the test set for demographic data, test health.csv - the test set for health related data, test habits.csv - the test set for habits related data.

The available data contains the following attributes:

**Sociodemographic Data**:
  - PatientID: The unique identifier of the patient.
  - Birth Year: Patient Year of Birth.
  - Name: Name of the patient.
  - Region: Patient Living Region.
  - Education: Answer to the question: What is the highest grade or year of school you have?
  - Disease: The dependent variable. If the patient has the disease (Disease = 1) or not (Disease = 0).

**Health Related Data**:
  - PatientID: The unique identifier of the patient.
  - Height: Patient’s height.
  - Weight: Patient’s weight.
  - Checkup: Answer to the question: How long has it been since you last visited a doctor for a routine Checkup? (A routine Checkup is a general physical exam, not an exam for a specific injury, illness, or condition.)
  - Diabetes: Answer to the question: (Ever told) you or your direct relatives have diabetes?
  - HighCholesterol: Cholesterol value.
  - BloodPressure: Blood Pressure in rest value.
  - Mental Health: Answer to the question: During the past 30 days, for about how many days did poor physical or mental health keep you from doing your usual activities, such as self-care, work, or recreation?
  - Physical Health: Answer to the question: Thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good to the point where it was difficult to walk?

**Habits related Data**:
  - PatientID: The unique identifier of the patient.
  - Smoking Habit: Answer to the question: Do you smoke more than 10 cigars daily?
  - Drinking Habit: Answer to the question: What is your behavior concerning alcohol consumption?
  - Exercise: Answer to the question: Do you exercise (more than 30 minutes) 3 times per week or more?
  - Fruit Habit: Answer to the question: How many portions of fruits do you consume per day?
  - Water Habit: Answer to the question: How much water do you drink per day?
