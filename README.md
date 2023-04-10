
# Autonomous Driving and AI for better cities
#### by Raul Cortes Vazquez

This project aims to demonstrate the safety of autonomous cars and the improvement of quality of life for people in cities by reducing traffic jams through simple application of AI.

## Overview
Automated cars are becoming increasingly prevalent in modern day cities, it is considered to be the future disruptive invention for the transport sector and therefore presents a good opportunity for those involved in it's development and implement. One of the biggest concerns towards them is their reliability and safety when compared with non autonomous vehicles.

This project will evaluate their safety and application for quality of life improvemet by reducing traffic through the use of AI. Safety will be evaluated through data related to car crashes and traffic reducing will be done through the use and processing of images from traffic cameras.


## Data Science Steps

#### 1 - Retrieving / Collecting Data
    Relevant data will be retrieved from the respective datasets.

#### 2 - Cleaning Data
    Data will be cleaned to keed the necessary information in order to answer the questions we have made.

#### 3 - Analyzing and exploring Data
    Data will be examined, inspected and treated as best suits our project goals.

#### 4 - Data Modelling
    Models will be built as requiered by our project and to demonstrate potential interaction between traffic cameras and ADS vehicles. 

#### 5 - Data Interpretation
    We will seek to show our findings.




## Data Cleaning

To clean the datasets we seek to obtain the best information for our project needs, therefore we want to keep records of ADS (Autonomously Driven Systems) and ADAS (Advanced Driver Assistance System), the dataset for other reflects different systems to the ADAS, however, these are non-autonomous and will therefore be grouped with the ADAS systems for better understanding of the data. Unnecessary columns and information will be removed.

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230948137-fc93b7dc-dbbe-4024-93a0-3763aef3736f.png">
</div>

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230948286-0cc4cc7b-f369-40a8-9339-08a16029c06c.png">
</div>

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230948395-54637242-d64b-408b-b0be-bb191f83daf4.png">
</div>

## Data Modelling

Data related to car accidents and the systems involved in driving them will be modelled to show how ADS fares in comparison to ADAS / Other.

### Visualizing 


Afterwards, we will show how reliable is ADS by comparing autonomously driven systems with non-autonomous driven systems and if there is a relation with a potential malfunctioning of the vehicle or if we could consider the human factor as remaining prevalent when it comes to car crashes.

### Traffic Camera Modelling

Data from traffic cameras in the form of imagery will be used to train a model built on Google's machine learning tool called Teachable. The model is meant to detect cars in red lights and traffic cameras, therefore, we will be feeding it with positive feedback through images from cars in traffic and then a negative one from roads and cities without any cars. 


After having been trained we import this model into our project and use it to evaluate different test images to see how our model works.


Our model is able to detect when cars are in an image or not, however, for it to be functional it must be improved to better detect and recognize more objects by adding additional classes and training to the model.


The model is now able to detect more objects and encircle them in a rectangle with their respective label. This can be further improved by using OpenCV Cascade Classifier Tool. This improves our object detection capabilities.

## Findings

There is no significant evidence to suggest there being a connection between car accident occurences with it being an ADS or non ADS system. This implies that it is worth continuing investing and growing automated cars capabilities, since these remove the human element which has been proven to actually influence on accidents. Usage of AI and interaction between vehicles on red lights could prove to be a good opportunity towards getting involved in the automated driving interaction among cars and a better quality of life for people in cities by reducing traffic through an easy application.
There are still several areas of opportunity in the data privacy, IoT security and autonomously driven cars segments, which will be important topics in the future and getting involved in the conversation this early on is a great opportunity for being part of this new technology that is just gonna get bigger.

## Repository Exploration



## Presentation


## Sources and references

#### References and sources that helped in the construction of this project
