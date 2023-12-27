# EthereumFraudDetection

Abstract : Machine learning models have already been
successfully used to accurately flag fraudulent accounts
on the ethereum blockchain [2]. But few have considered
what could happen if an attacker had full access to the
model pipeline. Indeed, while it is difficult to determine
the exact prevalence of whitebox attacks in the blockchain
industry, it would be naive to rely on pipeline secrecy for
security which is why it’s important to assess this type of
threat model. This study first implements high accuracy
machine learning models on an ethereum fraud dataset,
and then successfully shows that it’s possible to subtly
modify fraudulent account metadata to foil the model using
a generative adversarial model and astute data analysis.
The best model, an XGBoost tree, scored 99% accuracy
on the test set with a 0.95 f1 score for fraudulent accounts.
The generative model successfully camouflaged 20% of
fraudulent transactions with a modification vector of very
small norm. These results allow us to conclude that while
model accuracy is very high and it could indeed be used
as a tool to flag fraudulent accounts on the ethereum
blockchain, it’s not enough on it’s own because of low
robustness to informed attackers and that there is still
room for model improvement even if the accuracy metric
showcases very good results

# Dataset 
We worked on a dataset available on the following link : https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset

# Jupyter Notebooks 

FraudDetectionDataExploration.ipynb : Data Exploration, Data Cleaning, Data Visualisation, Statistical Analysis (Anova, Pearson) 

AdvExamples.ipynb : AdvGAN code

fraud_classifier.ipynb : All pipelines for Classification (Neural Networks and XGboost) 

