# **SchoolPool**

## A new way to get your kids to school.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

[//]: # (Images)

[image1]: ./images/Image1.png "Image 1"
[image2]: ./images/Image2.jpg "Image 2"
[image4]: ./images/Image4.JPG "Image 4"
[image5]: ./images/Image5.JPG "Image 5"
[image6]: ./images/Image6.JPG "Image 6"
[image7]: ./images/Image7.JPG "Image 7"
[image8]: ./images/Image8.JPG "Image 8"
[image9]: ./images/Image9.png "Image 9"
[image10]: ./images/Image10.jpg "Image 10"

## Goal of the project

Use the app to call your autonomous SpCar for your kid. The SpCar drives your kid safely to school.
Spend more time with your family in the morning and less time in the car. Project for BCW2018 Autonomous Driving Challenge. 

![image1]

## The SpCar

![image2]

The SpCar has Radar, Lidar and three cameras.

Radar and Linar collect data that are filtered using unscented and extended Kalman filters and particle filters.

The traffic camera collects data about the vehicles close to the car and the road lanes' position and curvature.

The traffic sign camera classifies the sign on the road using LeNet architecture.

The traffic light camera uses an advanced traffic light classifier. It uses MobileNet technique, Tensorflow models and Single-Shot Detection model.

Using the data from the three types of sensors the car can decide and drive autonomouly.

## The app

Use your phone number to sign in your account. SchoolPool data are hosted in a  Firebase online database. Secured and encrypted by Google.

![image4]

Find your school. Choose your destination. Use the "school" and "home" buttons or search for a new address.

![image5]

Choose your car. Choose one of the plans available for your route.

![image5]

Your phone unlocks the SpCar using NFC-key.  Get in the car and enjoy your ride.

![image7]

The design:

The SpCar was designed by Maria Dima, 5th year architecture student at Democritus University of Thrace.

![image8]
![image9]
![image10]

---


