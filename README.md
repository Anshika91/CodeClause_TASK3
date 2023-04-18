# CodeClause_TASK3

Name of Project--> Credit Card Fraud Detection

Software requirement IDE- Google Colab/Jupiter Notebook/PowerBI etc. Language- Python,R, etc. Datasets :- https://www.kaggle.com/

Description :  one of the most common cause of te accidents pn the road is sleepy drivers. in the USA each year drowsiness accounts for nearly 100k craches.
So it it essential to build a drivers drowsiness Detection system to avoid accidents that can detect wheather drivers are sleepy or not by looking and tracking their 
eye movement and alerting them with alarms. this project you can apply your computervision skill , such as CNN's and classify  wheather ddrivers are not sleepy.

Approach and WorkFlow: 

writing code : Python 
OverLaying : open CV
Tarining data : Transfer Learning (Deep Learning Concepts) Tensorflow

Methodology:
MRL Dataset--- > Transfer Learning
(MRL Dataset contains (37 men 4 women)


In the dataset , we annotated the following properties(the properties are indicated int the following order)

1)  Subject ID: in the dataset we collected the data of 37 different persons(33 men and 4 women)
2) Image ID:  the dataset consists of 84,898 images.
3)  Gender[0-man,1-women]: the dataset consists the information about gender for each image (men and women)
4) glasses[0-no,1-yes]:   the information if the eye image contains glasses is also provided for each image (with and without the glasses).
5) eye state[0-closed,1-open]: this property contains the information about two eye state (open ,close)
6.)reflections[0-none, 1-small, 2-big]: we annoated three reflection states based on the size of reflections (None,small and big reflections).
7) Lighting Conditions[0-bad,1-good]:each image has two states(bad,good) based on the ammount of light during captuaring the videos.
8) Sensor ID[01-RealSense,02-IDS,03-Aptina]: at this moment, the dataset contains the images captured by three different sensors(intel RealSense RS300 sensor with 640X480 resolution,IDS Imaging sensor with 1280X1024 resolution, and Aptina sensor with 752X480 resolution).
