# Classification-of-Acute Lymphoblastic Leukemia (ALL)-using-MobileNet-and-EfficientNetB3
The project involves the Classification of ALL using the Mobilenet and EfficientNetB3.

# DataSet
The work utilizes a  C-NMC Leukemia Classification dataset from Kaggle. 
The "Leukemia Classification Dataset" (also known as the "C-NMC Leukemia Classification" dataset) is a collection of medical images of blood cells 
For the purpose of classifying Acute Lymphoblastic Leukemia (ALL) vs. normal Hematopoietic cells (HEM). 
A total of 10,132 blood cell images are included in the collection, of which 2,253 are labeled as HEM and 7,879 are labeled as ALL

# Data Augmentation 
Here we use data augmentation as a data preprocessing technique to overcome the data imbalance problem in the given dataset.

# Model trained on MobileNet and EfficientNetB3
After the data augmentation, we train the model using the MobileNet algorithm and the EfficientNetB3 Algorithm(Pre-trained CNN Models).

# Test the models using testing data
Test both models using the testing data.

# Evaluate the performance of both model
Evaluate the performance of the models after testing and observe the results using some evolution metrics parameters like Accuracy, Precision, Recall, F1Score, Area Under curve, Accuracy-epoch curve, and Loss-Epoch curve.
after evaluating EfficientNetB3 gives better results than MobileNet for the given Dataset.

# Develop a Graphical User Interface using the MobileNet algorithm.
Develop a GUI, Where the user uploads the patient's microscopic blood image to check whether it contains ALL cancer or not.
