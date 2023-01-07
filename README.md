# Investigate-Medical-Appointment-Dataset
A person makes a doctor's appointment, receives all the instructions, and no-show. Who to blame?
In this project we will try to analyze why would some patient not show up for his medical appointment and whether there are reasons for that using the data we have.
We will try to find some correlation between the different attributes we have and whether the patient shows up or not.
The dataset we are going to use contains 110.527 medical appointments and its 14 associated variables
( PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handcap', SMS_received, No-show )

Questions to answer
What is the percentage of no-show?
What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
Is the time gender related to whether a patient will show or not?
Are patients with scholarship more likely to miss their appointment?
Are patients who don't recieve sms more likely to miss their appointment?
Is the time difference between the scheduling and appointment related to whether a patient will show?
Does age affect whether a patient will show up or not?
What is the percentage of patients missing their appointments for every neighbourhood

Conclusions
After analyzing the dataset here are some findings:
Percentage of patients who didn't show up for their appointment is 20.19%.
The percentage of females missing their appointment is nearly two times the number of males. So females are more likely to miss their appointment.
It appears that the longer the period between the scheduling and appointment the more likely the patient won't show up.
It seems that patients with scholarships are actually more likely to miss their appointment.
A strange finding here suggests that patients who received an SMS are more likely to miss their appointment !!
There is no clear relation between the age and whether the patients show up or not but younger patients are more likely to miss their appointments.

Analysis Shortcoming & Analysis Shortcoming & Data Limitations
The data doesn't state the exact hour of the appointment which would have been very useful to try to find out which hours have the most missing appointments and which doesn't. 
It could also be very useful to know the difference between scheduling and the appointment since many of the scheduling are on the same day.
The data doesn't state if any day is a vacation or not which can indicate if people tend to miss their appointments more on working days.
The age column had a negative value but according to the data creator, it means a baby not born yet (a pregnant woman).
When calculating the day difference between the scheduling and appointment days we had some negative value which makes no sense and might mean that the records of questions have wrong data.
