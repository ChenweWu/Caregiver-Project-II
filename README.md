# Caregiver-Project-II

# INTRODUCTION
 This project report illustrates how 1) the drug names with generics and classes were labeled,
and 2) how the Machine Learning techniques were used to predict the quality of life (QOL) of
caregivers of older patients with advanced cancer.

 For part 1, we designed an algorithm that cleans the raw dataset of drug names and labels drugs
with generics and classes using the existing reference dataset. Drugs name labeling can consume
a lot of time if done manually and computer algorithms can speed up the process. However, most
of the drug names do not have direct matches in the reference data and spelling errors exist a lot.
We were able to overcome these challenges using fuzzy matching and association rules generation
and develop an automation algorithm that can be potentially extended to other datasets.
 For part 2, we developed predictive models for caregiver outcomes. Caregivers are people who
help another person who can no longer be able to perform daily tasks necessary for everyday
survival alone. Old people with cancers depends on caregivers to support them at every stage of
the illness trajectory [1]. However, taking care of others itself can also adversely impact caregivers’
emotional and physical well-being, which is a phenomenon known as the caregiver burnout.
Caregivers might face significant level of stress when they do not meet the expectations. About
40% to 70% of caregivers suffer from depression, while many others also have anxiety and distress
as a result of pressure [2]. These long-term stresses are harmful for health. Hence it is crucial for
clinicians to identify and predict what specific groups of caregivers will have lower QOL and
potentially prevent the frustration.

In this clinical setting, six QOL outcome variables for caregivers were derived from two
questionnaires: one with Generalized Anxiety Disorder-7, Distress Thermometer, and Patient
Health, the other with Short-Form Health (SF12) survey. Previous literature has used logistic
regression models for prediction and analysis of the contributing factors to the deterioration of
caregiver QOL. We implemented, fine-tuned, and evaluated multiple machine learning models for
each of the 6 outcome variables and compared their results with Logistic Regression and saw a
significant improvement. The major challenge here is to deal with the data imbalance issue and
optimize model performance. A new technique called Local Interpretable Model-agnostic
Explanation (LIME) was also used to study the positive or negative effects of our predictors on
the caregiver QOL outcome variables. 
