# Capstone-project-2
 
Facial Recognition Attendance system
Project Proposal
 
 
Facial Recognition Attendance system
Taking attendance is a rather boring task. Let's see how we can automate this with artificial intelligence in python and a nice user interface in React. A system that check if a student is on time or has left early. But also, check the time of arrival and departure of those. We also want to be able to add or delete a student. We can place a camera in front of the door which will recognize the students and save the time of their arrival and departure. With those data we make some simple conditions to determine if they are late or if they left earlier. We save that information in an online database to make it accessible from anywhere. With a simple web interface. We just want to add and delete an student and check all the data we have about him. To create the front-end we use React which is perfect for processing information in real time. For the back-end, we use Python Flask to create an API which can receive request and data, then send back and answer. For example, the API will receive a name, make a request to the database to have all the data about this person and send back those data. For the database, we use PostgreSQL but any database engine would do the work. For the face recognition, we use a python library called "face_recognition".

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run train.py file

Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Creating a Folders:-

-Attendance

-ImagesUnknown

-StudentDetails

-TrainingImage

-TrainingImageLabel

Here I am working on Face recognition based Attendance Management System by using OpenCV.
One can mark thier attendance by simply facing the camera. 

How it works :

When we run train.py a window is opened and ask for Enter Id and Enter Name. After enter name and id then we have to click Take Images button.
By clicking Take Images camera of running computer is opened and it start taking image sample of person.This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. 
It takes 60 images as sample and store them in folder TrainingImage.After completion it notify that iamges saved.

Training :- After taking image sample we have to click Train Image button.Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.
Now all initial setups are done. By clicking Track Image button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. 
Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time and it is also available in window.

