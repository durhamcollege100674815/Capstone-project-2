# Capstone-project-2
 
Facial Recognition Attendance system
Project Proposal
 
 
Facial Recognition Attendance system
Taking attendance is a rather boring task. Let's see how we can automate this with artificial intelligence in python and a nice user interface in React. A system that check if a student is on time or has left early. But also, check the time of arrival and departure of those. We also want to be able to add or delete a student. We can place a camera in front of the door which will recognize the students and save the time of their arrival and departure. With those data we make some simple conditions to determine if they are late or if they left earlier. We save that information in an online database to make it accessible from anywhere. With a simple web interface. We just want to add and delete an student and check all the data we have about him. To create the front-end we use React which is perfect for processing information in real time. For the back-end, we use Python Flask to create an API which can receive request and data, then send back and answer. For example, the API will receive a name, make a request to the database to have all the data about this person and send back those data. For the database, we use PostgreSQL but any database engine would do the work. For the face recognition, we use a python library called "face_recognition".
