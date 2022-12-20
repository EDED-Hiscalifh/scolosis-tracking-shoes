# Project : Scolosis Tracking Shoes

- Project name : Scolosis observation project using foot pressure 
- Participation : Jeong Seok Gyu(201724570, PNU), Lee Doo Gyeong(201724525, PNU) 
- Proudct name : Scolosis tracking shoes 

# 1. Summarization 

|About product|Contents|
|:---:|:---| 
|Project name|Scolosis observation project using foot pressure| 
|Introduction|The foot pressure measurement device is a device that can measure the static foot pressure of a user, measure dynamic walking, and anlyze it, and is a user-friendly and easy to move. Within the project, a foot pressure measurement device was used to track the deepening and mitigration of scolosis, which is cost-effective compared to follow-up observation using conventional imaging equipment by measuring pressure differences in both feet. This work stores pressure sensor data measured through Bluetooth communication between Android and Apps in a smartphone, manipulates it through buttons in App Inventor application, and provides visualization plots with 2D Line chart and Table chart.| 
|The background and necessity| The number of patients with spinal diseases in Korea is steadily increasing. Among them, in the case of scolosis, follow-up observation using imaging equipment is emphasized. The need for a device for managing scolosis that team members are actually experiencing is reconsidered.| 
|The characteristics and advantages|We store the data obtained in real time through pressure sensor inside the database inside the application and provide a visualization plot for scolosis observation. It is a device that can observe the degree of scolosis through a simple self-measurement method without using an expensive device.| 
|The contents of the project|The work is divided into hardware and software parts. In the case of hardware, the pressure is measured through an FSR sensor, and the measured value is transmitted using Arduino's Bluetooth module. In particular, ArduinoIDE converts it into ADC units through the analogRead function and sends it to the application. In the software, the application was written through the App Inventor. The measured data is received in real time through Bluetooth communication, measured, and then the maximum pressure values of the measured pressures are extracted through a maximum-average value algorithm, calculated, and stored in TinyDB. In addition, visualization plots of stored data were provided as 2D Line-chart and Table-chart through the Google WebView API.|
|The expected effects and utilizations of the project|There is no need to move to medical institution to measure foot presure data through the product, so there are no spartial restrictions. Accessibility was improved using graph and charts to make it easire to interpret data by using user mobile devices.| 

# 2. Main text 

## 2.1 Overview 

### 2.1.1 Introduction

### 2.1.2 The background and necessity 

### 2.1.3 The characteristics and advantages 

## 2.2 The contents of the project 

### 2.2.1 The composition diagram

### 2.2.2 The functions

### 2.2.3 They key application techniques

### 2.2.4 The development environments

### 2.2.5 Other considerations

## 2.3 The project performance 

### 2.3.1 Participations' division of work 

### 2.3.2 Project execution scehdule 

### 2.3.3 Problems and solutions in the project implementation

### 2.3.4 The things i get through the project 

## 2.4 The expected effects and utilizations of the project 

## 2.4.1 The expected effects 

## 2.4.2 The utilizations 

## 2.5 Development outputs 
                                                                   
