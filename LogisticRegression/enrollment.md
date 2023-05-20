# Introduction
In the fall of 2014, the administration of a large private university requested that the Office of Enrollment Management and the Office of Institutional Research work together to identify prospective students who would most likely enroll as new freshmen in the Fall of 2015 semester. Historically, inquiries numbered about 90,000+ students, and the university enrolled from 2400 to 2800 new freshmen each Fall semester. It was decided that inquiries for Fall 2014 would be used to build the model to help shape the Fall 2015 freshman class.

Data was collated over a period of several months in consultation with Enrollment Management. Our task is to predict based on certain variables if a prospective student will enroll or not, thereby helping the institution channel its resources towards engaging with students that have the most potential to enroll.

We shall compare two classification models for this task, a logistic regression model and a classification tree model.

Below is the data dictionary that describes the entries in the file named enrollment.csv that accompanies the project.
# Data Dictionary

|----   Name---------------- |----  Description ------------------------|<br>
|ACADEMIC_INTEREST_1	|Primary academic interest code|<br>
|ACADEMIC_INTEREST_2	|Secondary academic interest code|<br>
|CAMPUS_VISIT	|Campus visit code|<br>
|CONTACT_CODE1	|First contact code|<br>
|CONTACT_DATE1	|First contact date|<br>
|ETHNICITY	|Ethnicity|<br>
|ENROLL	|1=Enrolled F2014, 0=Not enrolled F2014|<br>
|IRSCHOOL	|High school code|<br>
|INSTATE	|1=In state, 0=Out of state|<br>
|LEVEL_YEAR|	|Student academic level|<br>
|REFERRAL_CNTCTS	|Referral contact count|<br>
|SELF_INIT_CNTCTS	|Self-initiated contact count|<br>
|SOLICITED_CNTCTS	|Solicited contact count|<br>
|TERRITORY	|Recruitment area|<br>
|TOTAL_CONTACTS	|Total contact count|<br>
|TRAVEL_INIT_CNTCTS	|Travel initiated contact count|<br>
|AVG_INCOME	|Commercial HH income estimate|<br>
|DISTANCE	|Distance from university|<br>
|HSCRAT	|5-year high school enrollment rate|<br>
|INIT_SPAN	|Time from first contact to enrollment date|<br>
|INT1RAT	|5-year primary interest code rate|<br>
|INT2RAT	|5-year secondary interest code rate|<br>
|INTEREST	|Number of indicated extracurricular interests|<br>
|MAILQ	|Mail qualifying score (1=very interested)|<br>
|PREMIERE	|1=Attended campus recruitment event, 0=Did not|<br>
|SATSCORE	|SAT (original) score|<br>
|SEX	|Sex|<br>
|STUCELL	|1=Have a cell phone, 0=Do not|<br>
TELECQ	|Telecounciling qualifying score (1=very interested)|<br>
