# Prediction-of-disease-using-Radiograpy-images-
  The dataset is available in kaggle
  Link to download the dataset :- https://www.kaggle.com/tawsifurrahman/covid19-radiography-database
  The aim of this project to classify the radigraphy image among the four classes namely COVID,Lung Opacity,Viral Pneumonia and Normal(Healthy)
## Dataset 
  The dataset is heavily imbalanced.Training the model with this imbalanced dataset might lead to a biased model.
  So, Data balancing was performed on the Datased by oversampling on class Viral Pneumonia and Undersampling to classes Normal and Lung Opacity.
  The notebook COVID- Radiography (Data Balancing).ipynb contains the code for Data Balancing
## Model
  Tranfer learning was performed on State of art image classification models VGG16 and ResNet50
  VGG16- model with weights trained on Imagenet was used .
  Resnet50- was also used.
  These models were compared based on their performance and final model was selected
