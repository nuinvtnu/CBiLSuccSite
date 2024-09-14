# CBiLSuccSite: An efficient model for predicting protein succinylation sites.
With the aim of comprehensively studying and improving the prediction performance, we propose a prediction model, called **CBiLSuccSite**, for predicting protein succinylation sites.
# Requirement
- Google Colab Pro
- Keras
- Numpy
- Sklearn
- Pandas
- Server: TPUv2
# Dataset
The dataset originated from Hasan et al. [38] has been collected for the study. After some technical steps to remove data redundant and homologous data, a total of 2322 unique protein sequences (containing 5009 succinylated sites) has been obtained. 
In order prepare for training and testing dataset, the obtained dataset is then randomly separated into two sets: 
-  Training set: 2192 proteins (4755 positive and 4755 negative samples).
-  Testing set 1: 124 proteins (254 positive and 2977 negative samples).
-  Testing set 2: 124 proteins (254 positive and 254 negative samples)

# Train model: We use Google colab pro buid the model
  -  Cross validation: CV_CBiLSuccSite.ipynb
  -  Train model: Train_CBiLSuccSite.ipynb
    +  Save and name the trained model as Suci_CNN_BiLSTM.h5;
    +  Using the saved model Suci_CNN_BiLSTM.h5 (in the saved_folder) for learning and evaluating.
  - Independent test and predict: CBiLSuccSite_predict.ipynb

# Contact
Please feel free to contact us if you need any help: nvnui@ictu.edu.vn
