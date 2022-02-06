
# Potato Plant Disease Classification Classification

Convolutional Neural Networks (CNN), a technique within the broader Deep Learning field, have been a revolutionary force in Computer Vision applications, especially in the past half-decade or so. One main use-case is that of image classification, e.g. determining whether a picture is that of a dog or cat.
<br><br><br><image src="https://www.mdpi.com/agriculture/agriculture-11-00707/article_deploy/html/images/agriculture-11-00707-g004.png" style="width:100%"><br>
You don't have to limit yourself to a binary classifier of course; CNNs can easily scale to thousands of different classes, as seen in the well-known ImageNet dataset of 1000 classes, used to benchmark computer vision algorithm performance.
<br><br><br>


## Tool Reference

#### Get all items

```http
GET /api/Fastapi
```
```http
GET/pip install Tensorflow==2.7.0
```
```http
GET/HTML , CSS , JS
```
```http
GET/pip install Fastapi
```


## Documentation

I have used Hardcoding technique for this model as I wanted some practice with tensorflow and keras.

The Dataset had 3000 images in toatal which were then segregated in 80%-20% train-test segmentation. 

Then the train dataset is split into 70%-30% train-validation segmentation.

I have used DataAugmentation to increase the varaition of images in the dataset. 

The main Model consists of 16 layers from which 6 are combination of Conv2D & MaxPooling2D.

After this we test the model with the test images and save the model in Saved_Models
  


## Run The Model

The Application is hosted on https://localhost:8080/predict server.

**To run the model Run the main.py file from API folder and then run the main.html file from the frontend folder**

Now upload the image and click **predict**

You will see the Prediction as well as the confidence of its prediction.
  
  
  
## **Results**
After tuning a hard-coded model the accuracy of the model has reached till **98%**
