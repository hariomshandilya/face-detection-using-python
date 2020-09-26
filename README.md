# face-detection-using-python
The objective of the program given is to detect object of interest(face) in real time and to keep tracking of the same object.This is a simple example of how to detect face in Python. You can try to use training samples of any other object of your choice to be detected by training the classifier on required objects.
# OpenCV program to detect face in real time 
# import libraries of python OpenCV  
# where its functionality resides 
import cv2  
  
# load the required trained XML classifiers 
# https://github.com/Itseez/opencv/blob/master/ 
# data/haarcascades/haarcascade_frontalface_default.xml 
# Trained XML classifiers describes some features of some 
# object we want to detect a cascade function is trained 
# from a lot of positive(faces) and negative(non-faces) 
# images. 
