# Why Patients Miss their Medical Appointments

### Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)




### Introduction <a name="introduction"></a>

  The goal of this analysis is to investigate medical appointment dataset of one of public hospitals in Brazil. The data includes some attributes of patients and state if the patients showed up to appointments. The analysis will focus on finding the most factors that affecting patients attending to their medical appointments.


The Data include around 100k medial appointments which has the following variables

**Independent Variables:**

- PatientId: Identification of a patient
- AppointmentID: Identification of the appointment
- Gender: Male or Female
- ScheduledDay: The day where the appointment was registered in the system
- AppointmentDay: Actuall appointment date
- Age: Patient’s age
- Neighbourhood: Appointment site
- Scholarship: True or False, it indicates if the patient is in the Bolsa Familia program or not
- Hipertension: True or False
- Diabetes: True or False
- Alcoholism: True or False
- Handcap: True or False
- SMS_received: True or False, it indicates if the patient was received SMS reminder or not.

**Dependent Variables**

- No-show: Yes or now. it indicates if the patient showed up to their appointment or not.




> **By conducting this analysis, the following question will be answered:**

1. [How many patients are missed their appointments?](#q1)
1. [Predict most important factors that impacted patients attending to their medical appointments?](#q2)
1. [Find out impact of patient’s age and waiting time (time period between schedule date and appointment actual date) on the status appointment attending.](#q3)




### Installation <a name="installation"></a>

This project requires to install **Python** and the following Python's libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://ipython.org/notebook.html)

**Note:** you can install [Anaconda](http://continuum.io/downloads) if you don't have installed Python yet



### Project Motivation <a name="motivation"></a>

This Project was conducted as a part of Udacity Nanodegree Program in Data Science. I was interested on this subject because I already worked in public health care sector and I faced this problem on daily bases.


### File Descriptions <a name="files"></a>

This Project have the following files:

- [Medical Appointments.ipynb](https://github.com/ajmidana/Udacity_BlogProject/blob/master/Medical%20Appointments.ipynb) to find answers related to the above questions.
- [App_May_2016.csv](https://github.com/ajmidana/Udacity_BlogProject/blob/master/App_May_2016.csv) contain dataset that was used in current project.





### Results <a name="results"></a>
1. Analysis showed that around 20% of patients was missed their medical appointments that are from 29th April to 8th of June, 2016.<a name="q1"></a>

2. Analysis showed Age and waiting time (the time from the appointment is scheduled until actual appointment date) as the most factor that affected patients’ attending to their appointment.<a name="q2"></a>

3. Regarding the impact of patints’ age, Analysis showed that patients from 15 to 50 years are the ones who most likely to miss their medical appointments.<a name="q3"></a>

4. Analysis showed that the appointment with waiting time from 5 to 25 days are tend to be missed by patients.



### Licensing, Authors, Acknowledgements <a name="licensing"></a>

The data set was extracted from Kaggle website. You can refer to their online website to check the problem description and full detail by clicking [here](https://www.kaggle.com/joniarroba/noshowappointments/home)
