# Traffic Checker

Take image inputs and process them to show how crowded a street is. It detects both people and cars and shows how empty a street is. With possible future improvements, the accuracy of the model's detection could be increased with both more data and a larger model, for example resnet-50 or higher.
![image](https://github.com/user-attachments/assets/1adcc601-8693-4625-9591-44c9542c2932)

## The Model

The model works by using resnet-18 trained on a custom dataset made from images taken from google maps split into 3 classes. Those 3 classes are for streets with cars, people, and empty streets. The trained model will then decide how empty a street is. The model was trained several times with 30+ epochs to increase the accuracy of the model.

## Running this project

1. Select a test image to use in the code to run the model and name an output jpg to view which will show the percentage of emptiness.

## demo
https://drive.google.com/file/d/1PHsGcTpgFzD9gnMXnWWfr3L2SSkuUgid/view?usp=sharing
