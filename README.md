[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "dog"
[image2]: ./images/sample_human_output.png "human "


# Dog Breed Classifier(Convolutional Neural Network)

## Project Overview

This a Convolutional Neural Network(CNN) project in the Deep Learning Nanodegree at Udacity. This projects attempts at predicting the dog breed from the user supplied image.
And funnily enough if the user passes a human image, it will tell you the dog breed the human looks similar to.
Here's a sample output for a dog and a Human

![dog][image1]

![human ][image2]

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

	```
		jupyter notebook dog_app.ipynb
	```
  
  ## Project Information
  
  ### Contents
  
  * Intro
  * Step 0: Import Datasets
  * Step 1: Detect Humans
  * Step 2: Detect Dog
  * Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
  * Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
  * Step 5: Write Your Algorithm
  * Step 6: Test Your Algorithm
  
  ### Accelerating the Training Proecess
  
  In the training step in the Step 3 and 4, it is taking too long to run so you will need to either reduce the complexity of the VGG-16 architecture or switch to running the code on a GPU.
  
  #### Amazon Web Services
  
  You can use Amazon Web Services to launch an EC2 GPU instance.
