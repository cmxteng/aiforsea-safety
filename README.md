...In Progress...

<a href="https://www.aiforsea.com/"><h2 align="center">AI for S.E.A.</h2></a>
<p align="center">
  :bar_chart: Based on telematics data, how might we detect if the driver is driving dangerously? <strong>Safety</strong>
  <br><br>
  <a href="https://www.aiforsea.com/safety">
    <img alt="Traffic Management" src="https://static.wixstatic.com/media/397bed_e0fd4340ff5f40de876b26f0fb7e1f83~mv2.png/v1/fill/w_305,h_305,al_c,q_80,usm_0.66_1.00_0.01/Grab%20EDM_Safety.webp">
  </a>
</p>

___

<!-- TABLE OF CONTENTS -->
### Table of Contents

* [Grab Challenge](#Grab-Challenge)
  * [Problem Statement](#Problem-Statement)
  * [Objective](#Objective)
  * [Built With](#built-with)
* [Quick Link to Code](#Quick-Link)  
* [Prerequisites](#prerequisites)
* [Getting Started](#getting-started)
  * [Data Preparation](#Data-Preparation)
* [Feature Engineering](#Feature-Engineering)
  * [Train Test Data](#Train-Test-Data)
* [Data Visualization and Exploration](#Data-Visualization-and-Exploration)
* [Train the Regression Model](#Train-the-Regression-Model)
* [Model Comparison](#Model-Comparison)
* [The Optimum Model](#The-Optimum-Model)
* [Complete AI Model](#Complete-AI-Model)
* [Documentation](#Documentation)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

___

<!-- ABOUT THE PROJECT -->
## Grab Challenge
### Traffic Management
Based on telematics data, how might we detect if the driver is driving dangerously?

### Problem Statement
Given the telematics data for each trip and the label if the trip is tagged as dangerous driving, derive a model that can detect dangerous driving trips.

### Objective
Grab has been proactively pushing to make transportation in SEA safer. As part of the effort, we want to identify dangerous drivings in a timely manner.

### Built With
* [Anaconda](https://www.anaconda.com/)
* [Jupyter Notebook](https://jupyter.org/)
* [Spyder](https://www.spyder-ide.org/)
* [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)

**Submitted as Jupyter Notebook**

___

<!-- Quick Link -->
## Quick Link


___

<!-- Prerequisites -->
## Prerequisites
* 
```sh

```
* 
```sh

```
or
```sh

```

___

<!-- GETTING STARTED -->
## Getting Started
The given dataset contains telematics data during trips (bookingID). Each trip will be assigned with label 1 or 0 in a separate label file to indicate dangerous driving. Pls take note that dangerous drivings are labelled per trip, while each trip could contain thousands of telematics data points. participants are supposed to create the features based on the telematics data before training models.

* bookingID: trip id
* Accuracy: accuracy inferred by GPS in meters
* Bearing: GPS bearing in degree
* acceleration_x: accelerometer reading at x axis (m/s2)
* acceleration_y: accelerometer reading at y axis (m/s2)
* acceleration_z: accelerometer reading at z axis (m/s2)
* gyro_x: gyroscope reading in x axis (rad/s)
* gyro_y: gyroscope reading in y axis (rad/s)
* gyro_z: gyroscope reading in z axis (rad/s)
* second: time of the record by number of seconds
* Speed: speed measured by GPS in m/s

Abbreviation:

<!-- DATA PREP -->
### Data Preparation
    
___

<!-- FEATURE ENGINEERING -->
## Feature Engineering


<!-- TRAIN TEST DATA -->
### Train Test Data


___

<!-- DATA VISUALIZATION -->
## Data Visualization and Exploration

Click [complete code documentation]() to find the Data Visualization and Exploration.

___

<!-- TRAINING -->
## Train the regression model


Click [complete code documentation]() for quick view on the process of selecting the optimum model.

___

<!-- MODEL COMPARISON -->
## Model Comparison

___

<!-- OPTIMUM MODEL -->
## The Optimum Model


___

<!-- COMPLETE AI MODEL -->
## Complete AI Model
* Click [complete codebase]() for a complete test of my XGBoost model code. :star:

___
<!-- DOCUMENTATION -->
## Documentation
* Click [complete code documentation]() for a quick view of my code documentation from getting start to the best model I obtained.

___

<!-- CONTACT -->
## Contact

Teng Chun Man - [@linkedin](https://www.linkedin.com/in/tengchunman/)

Email: tengchunman@gmail.com

___

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
