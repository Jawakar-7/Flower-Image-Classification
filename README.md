# Flower-Image-Classification

A flower bouquet shop wants to enhance its customer experience by implementing an image classification component. The goal is to create a mobile app that allows customers to take pictures of flowers they encounter and receive information about the flower species, care instructions, and the option to order similar flowers. 

#Dataset Description
The dataset consists of 5 different flower classes. Lilly, Lotus, Sunflower, Orchid and Tulip. Each flower class has 1000 images. Multi-class CNN can be performed on this dataset to classify the flower belonging to the mentioned above 5 classes.
<img width="629" alt="image" src="https://github.com/Jawakar-7/Flower-Image-Classification/assets/94454751/cffe572f-73b3-4542-a21c-058a9e3d5131">

Dataset Link:https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset/data

# Preprocessing and loading
Data Preprocessing and loading are done by using Keras Image Data Generator  where I have split the model 0.2% for Validation purposes.

# Modelling 
The Model I have used is a Custom CNN Model with 4 Convolutional Layers with batch normalization and dropout and pooling layers.
I have used Callback functions to reduce Overfitting and Model monitoring
The model has 
total params: 1976101 (7.54 MB)
Trainable params: 1975781 (7.54 MB)
Non-trainable params: 320 (1.25 KB)

The model has Training accuracy of 94 and Validation accuracy of 87
![image](https://github.com/Jawakar-7/Flower-Image-Classification/assets/94454751/78b9806d-e2e8-44ef-9038-4bd5083155e2)


# Metrics :
I have used  classification metrics such as the Confusion Matrix.
![image](https://github.com/Jawakar-7/Flower-Image-Classification/assets/94454751/9f87697a-55d7-442e-a0fd-3e983005c2d1)





