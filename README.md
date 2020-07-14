# fire_and_smoke_detection

# Dataset
An image dataset for training fire and frame detection AI
<strong> Fire-Flame-Dataset </strong> is a dataset collected in order to train machine learning model to recognize Fire, smoke, and neutral(images without fire or smoke).This a dataset containing about 3000 images and 3 classes which include:
* Fire 
* Smoke
* neutral 
<br>

There are 1000 images in each category and 900 for train and 100 for testing

### Training and Prediction
 
The implementation code in which the model was train with has been provide in this repository. The model was trained with train with resnet50 and a accuracy of 85% on the test data was achieved. The python codebase is contained in fireandsmoke.ipynb. 

<strong>Some of the prediction results are shown below:</strong> <br>
![fire](./results/fire.png)
> ('Image of:', 'Class: Fire', 'Confidence score: 1.0') 

![nuetral](./results/nuetral.png)
> ('Image of:', 'Class: Fire', 'Confidence score: 0.990234375') 

![smoke](./results/smoke.png)
> ('Image of:', 'Class: Neutral', 'Confidence score: 0.99365234375') 


### Reqirements
___
* Python 3
* Pytorch
* Numpy
* Matplotlib
* TorchFussion
