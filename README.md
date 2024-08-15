# CBiLSuccSite

CBiLSuccSite: A Hybrid Deep Learning Model for Succinylation Sites Prediction.

In an attempt to thoroughly understand and improve the efficiency of predicting protein succinylation sites, we propose a hybrid deep learning model called CBiLSuccSite, which combines Convolutional Neural Networks (CNN) and Bidirectional Long Short-Term Memory (Bi-LSTM) networks. Our model leverages word embedding features of proteins, enabling it to capture complex patterns and dependencies in protein sequences. Unlike previous models, our approach does not require manual feature extraction; instead, we use a word embedding layer to automatically discover the features of protein language.

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
