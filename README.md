[Human Emotions Clasification.docx](https://github.com/SwatiNighut/Human_Emotion_classification/files/8031667/Human.Emotions.Clasification.docx)
# Human_Emotion_classification


Human Emotions Clasification

This project is based on Computer vision.

Dataset:
The dataset of images is taken from Kaggle.

Objective:
The main objective of this project is to classify the human emotions and also do live face emotion detection through webcam.

Tools and techniques used:
Different operation of python, deep learning & NLP,  computer vision are used.
Numpy , pandas, tensorflow , keras  ,cv2  these libraries used in project.

Steps of classification:
1)	Get the data,divide the data into train and test.
2)	Used Imagedatagenerator to generate batches of images and done some preprocessing, normalization.
3)	Building the model using convolution Neural Network, Maxpooling layer, dense layer, flatten layer.
4)	Train the model using Adam Optimizer.
5)	Finally gets the evaluation using accuracy metrics.

When the model preparation is done I converted it into json and h5 file format.
Using face haarcascade a python code is written to do live face detection and identification of emotion.
This model gives the 67% accuracy.









