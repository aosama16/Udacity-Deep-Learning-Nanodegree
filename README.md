![Certificate](https://user-images.githubusercontent.com/44305804/85444895-1aa40c00-b593-11ea-9d94-ac537eb05f04.jpg)

# Udacity-Deep-Learning-Nanodegree
This repository's purpose in to document my projects submission to Udacity's [Deep Learning Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

To Run any of the projects on your local machine please run these commands to create a conda environment
```
conda env create -f environment.yml
conda activate deep-learning
```

![project1](https://user-images.githubusercontent.com/44305804/83665787-33d91e80-a5cc-11ea-80d4-1c2313e06db5.png)
Implemented a neural network from scratch in NumPy to predict bike rentals.

Data Set Size: 17379 Records

Dataset<br>
Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions,
precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The core data set is related to  
the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is 
publicly available in http://capitalbikeshare.com/system-data. We aggregated the data on two hourly and daily basis and then 
extracted and added the corresponding weather and seasonal information. Weather information are extracted from http://www.freemeteo.com. 

------

![project2](https://user-images.githubusercontent.com/44305804/83665790-3471b500-a5cc-11ea-9652-cb2d589bb584.png)
Built a convolutional neural network using PyTorch to classify any image (even an image of a face) as a specific dog breed.

Main Tasks
- Create a CNN to Classify Dog Breeds from Scratch using PyTorch
- Create a CNN to Classify Dog Breeds using Transfer Learning from a VGG16 Model

Dataset<br>
[Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/), Size: 13233 records<br>
[Dog Data Set](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip), Size: 8351 records

------

![project3](https://user-images.githubusercontent.com/44305804/83665793-350a4b80-a5cc-11ea-8915-9f955bbd8a80.png)

In this project, i generated Seinfeld TV scripts using RNNs. The Neural Network will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

Dataset<br>
[Seinfeld Chronicles](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv)<br>
Complete Seinfeld Scripts and Episode Details

Content<br>
Details about all the episodes.<br>
Includes attributes like Director, Episode Name, Air Date etc…<br>
Complete Scripts of all the episodes.<br>

------

![project4](https://user-images.githubusercontent.com/44305804/83665796-35a2e200-a5cc-11ea-87bf-c18c2ecbfe01.png)

In this project, i defined and trained a DCGAN (Deep Convolutional Generative Adversarial Network) on a dataset of faces. <br>
My goal was to get a generator network to generate new images of faces that look as realistic as possible!

Dataset<br>
[CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. The images in this dataset cover large pose variations and background clutter.

Modification on the dataset<br>
- The image input has been cropped to focus on the face.
- The image input has been resized to be a 32 * 32 pixel image.
- Used a smaller subset of the very large CelebA data.

------

![project5](https://user-images.githubusercontent.com/44305804/83665798-363b7880-a5cc-11ea-9cbf-b457f42e0046.png)

In this project i trained a RNN (Sentiment analysis model) to classify IMDB movie reviews (Positive and Negative) using Amazon's AWS, it was deployed to a web app using Lambda and API Gateway.

Dataset<br>
[Large Movie Review Dataset](http://ai.stanford.edu/~amaas/data/sentiment/) is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. Raw text and already processed bag of words formats are provided.

Main Tasks
- Train a RNN model using an Amazon EC2 instance.
- Deploy the model by creating an endpoint.
- Setting up a Lambda function for creating the backend service.
- Setting up API Gateway for creating the REST API.

------
