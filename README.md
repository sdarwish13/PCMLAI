## IMAGE CLASSIFICATION


This project involves building an image classification model using Convolutional Neural Networks (CNN) and the Intel Image Classification dataset. The goal of this project is to teach the computer how to accurately identify different image scenes, such as buildings, mountains, and glaciers.
To do this, I use a type of deep learning algorithm called a CNN, which is designed to process visual information like images. By training the model on the Intel Image Classification dataset, which contains thousands of images of different natural scenes, I was able to teach the model to recognize patterns in the images and classify them into different categories.
Once the model is trained, it will be able to accurately classify new images that it has never seen before.

The data I used is the Intel Image Classification dataset. It consists of almost 25000 images of buildings, forest, glacier, mountain, sea, and street. The data is separated into 3 folders: train, test, and prediction, where 17000 images are in train, 3000 in testing and 7000 in prediction. I found the dataset on kaggle and due to its size it is not included in this repository. 
Link to dataset: https://www.kaggle.com/datasets/puneet6060/intel-image-classification

For the model i used Convolutional Neural Network. When I first chose my problem, before I started with the code, I wanted to get an idea of how to work on this problem, so I started with researching what the best model would be for an image classification problem. After doing this research I found out that the best model to use with images and image classification was CNN.

For the hyperparameters, I went for the trial and error way. So I first started with an input layer and 2 hidden layers and 2 dense layers, this architecture was inspired from an online article. With this architecture I didn't get the results I wanted so I went with the recommendation of this same article that said that I should add layers for more complex problems, so I added one hidden layer and one dense layer. For the number of epochs and batches I also went with the trial and error method, where I fist tried 10 epochs thought the model could do better so adde to 20 epochs and then settled at 30. And with the number of batches I started with 30 but then changed it to 25 and settled for that number.

After training the model for 30 epochs, the results I got were satisfying since the accuracy was above 85% and the validation accuracy was above 80%. And when trying the model prediction with a few new images, the model got them all correctly which i found quite impressive.
