# CamCapture_Offloading3
Mobile Offloading Android Application

Title - Android Image Classification and
Offloading

Background and Motivation - Computational offloading is a critical technology
for emerging edge computing and Internet of
Things (IoT). Offloading is a technique to increase
mobile device’s capability by dividing the problem
and migrating the computation to other more
resourceful devices or servers located nearby. This
improves the application performance as well as
serves as a solution for the limited resources of IoT
devices. This project demonstrates computational
offloading in edge computing by offloading the task
to multiple flask servers, thereby increasing speed and
accuracy, as well as reducing the computational cost.

Goal of the project - The goal of this project is to use an Android application to
partition handwritten digit images into 4 parts and send them to 4 different servers for
classification. The classification is done by training a machine learning model (CNN) on the
MNIST dataset in order to predict the image parts received. Following the classification of the image parts on the 4 servers, the results
along with the accuracy of classification is sent back to the master mobile. The master
mobile then selects the classification based on highest accuracy, and places the digit image
in the relevant folder on the mobile internal storage.

Install - 
1. Start the flask server on 4 different laptops by running the main.py file, and run the
ngrok tool to expose the localhost to the public domain.
2. Install the application on the master android mobile.

