
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

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230948588-3ccbf0a1-4eb4-41d3-9feb-f4ce17939aea.png">
</div>

Afterwards, we will show how reliable is ADS by comparing autonomously driven systems with non-autonomous driven systems and if there is a relation with a potential malfunctioning of the vehicle or if we could consider the human factor as remaining prevalent when it comes to car crashes by analyzing groupped data between ADS and non ADS models.

<img width="747" alt="image" src="https://user-images.githubusercontent.com/115320501/230948855-49c54602-7934-4828-b3d3-a8855c805da4.png">

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230948985-7060b955-5641-489a-87bb-6b7905dd1058.png">
</div>

### Traffic Camera Modelling

Data from traffic cameras in the form of imagery will be used to train a model built on Google's machine learning tool called Teachable. The model is meant to detect cars in red lights and traffic cameras, therefore, we will be feeding it with positive feedback through images from cars in traffic and then a negative one from roads and cities without any cars. 

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230949363-0284c271-5567-4d95-b152-4e68c93117a0.png">
</div>

After having been trained we import this model into our project and use it to evaluate different test images to see how our model works.

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230949534-2b9def34-8570-45ad-9fae-baa511fbcfba.png">
</div>

Our model is able to detect when cars are in an image or not, however, for it to be functional it must be improved to better detect and recognize more objects by adding additional classes and training to the model.

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230949771-4d12c1ee-5d80-4fa8-a385-ecfb1f186418.png">
</div>

The model is now able to detect more objects and encircle them in a rectangle with their respective label. This can be further improved by using OpenCV Cascade Classifier Tool. This improves our object detection capabilities.

<div align="center">
<img src= "https://user-images.githubusercontent.com/115320501/230949985-82ec61d0-7a47-4191-9d09-f0c2b18e99e4.png">
</div>

## Findings

There is no significant evidence to suggest there being a connection between car accident occurences with it being an ADS or non ADS system. This implies that it is worth continuing investing and growing automated cars capabilities, since these remove the human element which has been proven to actually influence on accidents. Usage of AI and interaction between vehicles on red lights could prove to be a good opportunity towards getting involved in the automated driving interaction among cars and a better quality of life for people in cities by reducing traffic through an easy application.
There are still several areas of opportunity in the data privacy, IoT security and autonomously driven cars segments, which will be important topics in the future and getting involved in the conversation this early on is a great opportunity for being part of this new technology that is just gonna get bigger.

## Repository Exploration
The repository has a data folder which contains all datasets and imagery that was used for the project as well as the designated models used and created for image processing. The repository also contains a folder with the jupyter notebook checkpoints and the Final_Project.ipynb file containing the project itself. Additionally, the repository also contains a lin_reg.py file which is used when making a regression. Finally, the repository also contains the Capstone_Project_Proposal.pdf which is the original project proposal, the Final Presentation AutonomousCarsNonTechnicalR.pptx and a pre_presentation folder containing the previous presentation and this README.md file.

## Presentation
https://github.com/raulc23d/CapstoneProjectR/blob/main/AutonomousCarsNonTechnicalR.pptx

## Sources and references
#### Bibliography that helped in the construction of this project

https://pubmed.ncbi.nlm.nih.gov/11297224/

https://www.sfmta.com/projects/driving-automation-systems-advanced-driver-assistance-systems-adas-and-automated-driving#:~:text=%E2%80%9CDriving%20automation%E2%80%9D%20refers%20to%20both%20Advanced%20Driver%20Assistance,to%20operate%20a%20vehicle%20without%20a%20human%20driver.

https://docs.opencv.org/2.4/doc/user_guide/ug_traincascade.html

https://docs.opencv.org/2.4/modules/objdetect/doc/cascade_classification.html?highlight=car%20detection#void%20CascadeClassifier::detectMultiScale(const%20Mat&%20image,%20vector%3CRect%3E&%20objects,%20double%20scaleFactor,%20int%20minNeighbors,%20int%20flags,%20Size%20minSize,%20Size%20maxSize)
