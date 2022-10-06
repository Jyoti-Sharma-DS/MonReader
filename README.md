## zPCUcppWq64WWzzY
 
#   Mon Reader 
 

## Project Overview:
The main objective of the startup is to build a new mobile document digitization experience for the blind. The problem to be solved in this project is to identify if book images contain flipped pages or not. The company intends to use these labeled images as input for another machine learning model. This project's goal is to build a machine learning model that can label the book images as 'flip' or 'not flip'.

# Exploratory Data analysis Findings:

The data belongs to an organization which develops innovative Artificial Intelligence and Computer Vision solutions. The data provided contains images labelled as 'flip' and 'not flip'. The dataset contains 

|  | Dataset type  | Total Records #    | Flip count #   | Not flip count # | 
|---|---|---|---|---|
| 1 | Train Dataset  | 2392       | 1162   | 1230     |
| 2 | Test Dataset  | 597    | 290   | 307     |


# Machine Learning model used:
To design the best model for accurately predicting the image labels I have experimented with a custom neural network and Pre-Trained EfficientNet models.

The summary of the trained model looks like 

|  | Model Name  | Accuracy Test Data   | F1-Score Test Data   | Best Accuracy Validation Images | Training Images Accuracy  |
|---|---|---|---|---|---|
| 1 | Custom CNN  | 76.549% | 0.76   |   76.6%   |  98.3%    |
| 2 | EfficientNet Pre-Trained  |98.32%    | 0.98   | 99.1%    | 98.9% |


<br> 
The code for the model can be found in below notebook <br>
Notebook Link :  https://nbviewer.org/github/Jyoti-Sharma-DS/MonReader/blob/main/MonReader_CNN.ipynb

# Conclusion:
The EfficientNet model with pretrained layers works best for out dataset. We are able to 98.8% accuracy in classifying Test images
