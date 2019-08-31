# Image Caption Generator

Image caption generator is a model which generates a caption that describes the contents of the image. It requires a model from computer vision to understand the content of the image and a language model from NLP to translate the understanding of the image into words.


![](Images/caption.png?raw=true)

Deep Learning Models have provided an excellent way to get results for examples of this problem.

<br>

## Dataset:
[FLICKR_8K](https://forms.illinois.edu/sec/1713398).
This dataset includes around  images along with 5 different captions written by different people for each image.

![](Images/dataset_image.PNG?raw=true)
<br>

## The Block diagram of model used in the project

![](Images/model_sequence.png?raw=true)
<br>
![](Images/explain_model.png?raw=true)
<br>

## Flow of the Project

#### 1. Cleaning the Captions
#### 2. Extracting Features of image
#### 3. Preprocessing of  Image and Text Data
#### 4. Training on LSTM Model
#### 5. Predicting Captions and Evaluating performance

<br>

### VGG Model Summary

Pre trained VGG16 Model has been used to extract the features of the image.

![](Images/vgg16.png?raw=true)

<br>

### LSTM Model Summary

![](Images/lstm_model.PNG?raw=true)

<br>

## Predictions by the model 

![](Images/predict1.PNG?raw=true)

![](Images/predict2.PNG?raw=true)

<br>

## Evaluation using BLEU score

![](Images/good.PNG?raw=true)

![](Images/bad.PNG?raw=true)


## Conclusion

The Model has successfully generated captions for images. The performance of the model can be further improved by hyperparameter training.
