Introduction

This was a personal project for practicing training and implementation of detection AI. I wanted the model to be able to go through different media to detect fish. Essentially, the model would go over the input (various types of media) and outline and give a confidence rating for teach object it thought was a fish. 

Dataset

My dataset consisted of 11 images I took of my aquarium at my house, on my iPhone, which I then manually labeled and created a dataset using Roboflow. 

Model

I trained my model using YoloV8's pre-trained model. Given my lower-end GPU, it was not able to efficiently train the model with too many epochs, so I chose to use 3 Epochs, which would still give me a usable model within a timely matter. 

Implmentation

The code for implementation can be seen in 


