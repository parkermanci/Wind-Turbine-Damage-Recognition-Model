# Wind-Turbine-Damage-Recognition-Model

I built an image classification model that can make this process more efficient, as it can determine whether a wind turbine is damaged or not damaged based off of an image. I worked in PyCharm and used scikit-learn for the body, as shown in the picture above, and was able to achieve an accuracy rate of about 70%. 

To summarize how it works, it takes in file of images during training that it resizes and sorts into categories. It then splits the data into a training set and testing set, and creates multiple image classifiers to find the best one for the data. Once it find this, it predicts the labels for the test set. 
