# Udacity_no_show_apptmts
Investigating data using Pandas
Dataset Description

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família(opens in a new tab).
'No-show': it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show

Questions for Analysis

1.Does appointment scheduled much earlier has any effect on no_show?

2.In which location most of appointments are not honored?

3.Which age group has more diabetic and hypertension?

4.What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

Conclusions

This data collected from April 29th to June 8th, which is just 40 days of data. This short period data cannot be reliable to make strong conclusion on correlation.
1.Does appointment scheduled much earlier has any effect on no_show?

    By comparing days difference with no show data, its clear both are following same pattern irrespective of increase in days.But appointments booked within 30 days has higher show rate

2.In which location most of appointments are not honored?

    Location Itarare, Jesus De nazareth has no show of 26% , 24% respectively.
    We can conclude that Location Itarare has high no-show. This may lead to further investication on Why?
    Is there any issue in service? Does location has any other facility drawback? for that analysis we need some more data.

3.Which age group has more diabetic and hypertension?

    Age group above 60 has more patients with Hypertension and Diabetes.

4.What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

    The following factors might have impact on predicting if the patient will show up for their scheduled appointment
        Age group
        Alcoholism
        SMS received has negative impact
        Days difference between schedule and appoinment day
