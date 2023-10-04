# MyWay

# Abstract

There are many problems that face transportation movement such as Driving Behavior and Attitude, Traffic Accidents, Road and Environment Incidents. 

Our main problem that we chose is Road and Environment Incidents. We chose this problem as people ignore it even though it is one of the most important transportation issues.

Road and Environment Incidents include ground crashes, pipeline explosions, falling rocks, tree crashes, rains and floods, fire and explosions. 

Maintaining and fixing these problems as early as possible reduces the possibility of accidents.

We came up with this idea to help the government to fix these issues as early as possible, and users to be up to date with road issues to avoid being in danger.

We developed a mobile application to make users report incidents easily and fast using their mobile camera which images captured will be processed by our AI model.

On the other hand, we have a web application to monitor reports and help admins to manage them.


# AI Model Architecture

The **`InceptionV3 model`** with pre-trained weights from ImageNet is used as the base model.
The pre-trained layers are frozen to prevent them from being updated during training.

Additional layers are added on top of the base model, including a global average pooling layer, batch normalization, and dense layers with dropout for regularization.

The number of output neurons in the last dense layer corresponds to the number of classes in the dataset, and SoftMax activation is applied for multi-class classification.


# Mobile Application 

For the implementation of our mobile application, we utilized the **`Flutter framework`**. 
which allowed us to create a high-quality, visually appealing, and performant application for both the Android and iOS (iPhone Operating System) platforms using a single codebase.

# Website Application

For the implementation of our website application, we utilized **`Laravel framework`** for the backend due to its many useful features.

For the frontend, we chose **`React framework`** due to its SPA (Single Page Application) feature, which results in a lightweight and faster website.





### Devolepment team:
Mohammed Khaked Sabrah:         mohammed55230@gmail.com

Mahmoud Mustafa El Sayed:       mahmoud.mustafa.60331@gmail.com

Mariam Mohamed Abdelraouf:      mariamhilal25@gmail.com

Ahmed Ashraf Ahmed:             ahmeddashraff02@gmail.com

Hamdi Hossam Hamdi:             Hamdihossam461@gmail.com




 

