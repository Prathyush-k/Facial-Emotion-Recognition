# Facial-Emotion-Recognition
##### Current Status: *Working*

Experimenting with various image recognition models to classify the emotions displayed.


## Dataset
Source: [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)

The data consists of images of faces which are stored in folders with labels as the name of the folder. 
The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). 

The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

## Models
### Model 1 - CNN:
I build a custom CNN model and trained it using the available data.

### Model 2 - Resnet50:
I am using Transfer Learning. Utilizing a Resnet50 model trained on imagenet data set to identify facial emotions.

## Results (Accuracy)
### Model 1 - CNN:
Accuracy: 59%

### Model 2 - Resnet50:
Accuracy: Model training in progress


## Real-Time Prediction
In "Model Use.ipynb" we can use the model in real-time.


