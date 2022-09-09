# Interpreting Room Data - Determining Sensor Data Statistics

## Introduction

This pdf is the report of my experiments with available sensor data collected at Intel Laboratories. The goal is to determine the statistical correlation of sensor data based on its spatial and temporal distance.
 
## Dataset

The link for the dataset used for this experiment is: [Intel Lab Data (mit.edu)](http://db.csail.mit.edu/labdata/labdata.html)

[Mica2Dot](http://www.xbow.com/Products/productsdetails.aspx?sid=73) sensors with [weather boards](http://www.xbow.com/Products/productsdetails.aspx?sid=84) collected timestamped topology information, along with humidity, temperature, light and voltage values once every 31 seconds. Data was collected using the [TinyDB](http://telegraph.cs.berkeley.edu/tinydb) in-network query processing system, built on the [TinyOS](http://webs.cs.berkeley.edu/tos/) platform.

The sensors were arranged in the lab according to the diagram shown below: 

![image](https://user-images.githubusercontent.com/63736000/189357204-07732d29-a907-4453-a410-234fdfa0c1bf.png)


## Experiments Performed

1. Calculated temporal and spatial correlation between the datasets of a sensor.
2. Calculated spatial correlation between datasets of two sensors close to each other as well as sensors located far away from each other.
3. Predicted the missing data for sensor 1 using various prediction techniques.

# Interpreting Human Activity - Human Activity Detection using Accelerometer and Gyroscope Data

## Introduction

This pdf is my report of working with sensor data collected using accelerometer and gyroscope. The objective is to detect human activities like standing, sitting, walking, climbing up/down the stairs, etc. through decision fusion algorithms. In addition, behaviour change detection algorithms have also been used to detect points of switching between these activities in given time.

## Dataset

The link for the dataset used for this experiment is: [UCI Machine Learning Repository: Human Activity Recognition Using Smartphones Data Set](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

The dataset is built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.

## Experiments Performed

1. Plotted sensor data for each activity. 
2. Developed models for activity detection and behaviour change detection. 
3. Experimented with sensors data individually as well as together to estimate the best combination of sensors for activity detection.
