# CBiLSuccSite

CBiLSuccSite: A novel approach for the prediction of succinylation sites based on a hybrid deep learning model and word embedding features of protein.

# Requirement
- Google Colab Pro
- Keras
- Numpy
- Sklearn
- Pandas
# Dataset
The dataset originated from Hasan et al. [38] has been collected for the study. After some technical steps to remove data redundant and homologous data, a total of 2322 unique protein sequences (containing 5009 succinylated sites) has been obtained. 
In order prepare for training and testing dataset, the obtained dataset is then randomly separated into two sets: 
-  Training set: 2192 protein sequences (4755 positive, 4755 Negative).
-  Testing set: 124 proteins sequences (254 positive, 254 negative).

# Train model: We use Google colab pro buid this model
  -  Cross validation: CV_CBILSuccSite.ipynb
  -  Train model: Train_CBILSuccSite.ipynb.
  + Save and name the trained model as LBiPlantUbi.h5
  + Use LBiPlantUbi.h5 in the saved_folder for predicting
- Independent test and predict: CBILSuccSite_predict.ipynb

# Contact
Please feel free to contact us if you need any help: nvnui@ictu.edu.vn
