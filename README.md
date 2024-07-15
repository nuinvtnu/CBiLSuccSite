# CBiLSuccSite

CBiLSuccSite: A novel approach for the prediction of succinylation sites based on a hybrid deep learning model and word embedding features of protein.

# Requirement
  - Google Colab Pro
	- Keras
	- Numpy
	- Sklearn
	- Pandas
# Dataset
In order to prepare training and testing datasets for the work, the dataset of 2322 protein sequences has been randomly separated into two sets: 
-  Training set: 2192 protein sequences (4755 positive, 4755 Negative).
-  Testing set: 124 proteins sequences (254 positive, 254 negative).

This process yielded 7000 protein fragments from the plant data subset, with 3500 positive and 3500 negative fragments selected randomly.
	- The independent dataset: 1500 sequences were chosen at random from the total fragments (750 positive and 750 negative)
	- The training set: 5500 fragments (2750 positive and 2750 negative).
# Train model: We use Google colab pro buid this model
  -  Cross validation: CV_CBILSuccSite.ipynb
  -  Train model: Train_CBILSuccSite.ipynb.
    +  Save and name model as Suci_CNN_BiLSTM.h5.
    +  Use Suci_CNN_BiLSTM.h5 in the saved_folder for predicting.
  -  Independent test and predict: CBILSuccSite_predict.ipynb

# Contact
Please feel free to contact us if you need any help: nvnui@ictu.edu.vn
