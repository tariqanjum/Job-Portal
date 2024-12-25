# Job-Portal
The Job Portal is an online platform designed to bridge the gap between job seekers and employers, simplifying the recruitment and job-hunting process. It serves as a centralized hub where companies can post job openings and individuals can search for opportunities, apply, and manage their career growth.
# create database with name xyz..
Table 1 : applications
Columns:
Application_id int AI PK 
job_id int 
user_id int 
name varchar(100) 
email varchar(100) 
phone varchar(12) 
experience enum('Fresher','Experienced') 
appliedDate date 
skills text 
status varchar(20)
-------------------------------------
Table 2: jobs
Columns:
job_id int AI PK 
user_id int 
job_title varchar(100) 
company_name varchar(100) 
company_logo varchar(255) 
j_location varchar(100) 
job_type varchar(100) 
salary varchar(100) 
experience_level varchar(100) 
skills varchar(100) 
posted_date date 
application_deadline date 
job_description text 
job_category varchar(100) 
required_qualifications text 
contact_information varchar(100) 
vacancy int 
percentage varchar(100) 
status varc
----------------------------------------------------------
Table 3 : jobs
Columns:
job_id int AI PK 
user_id int 
job_title varchar(100) 
company_name varchar(100) 
company_logo varchar(255) 
j_location varchar(100) 
job_type varchar(100) 
salary varchar(100) 
experience_level varchar(100) 
skills varchar(100) 
posted_date date 
application_deadline date 
job_description text 
job_category varchar(100) 
required_qualifications text 
contact_information varchar(100) 
vacancy int 
percentage varchar(100) 
status varc
-------------------------------------------------------------------------

Table 4: seeker
Columns:
seeker_id int AI PK 
id int 
name varchar(45) 
phone varchar(15) 
email varchar(45) 
dob date 
gender enum('male','female') 
address varchar(255) 
qualification varchar(155) 
specialization varchar(145) 
tenth decimal(5,2) 
twelfth decimal(5,2) 
experience enum('experienced','fresher') 
period decimal(3,2) 
picture varchar(255) 
skills text
-------------------------------------------------------------
Table 5: users
Columns:
id int AI PK 
name varchar(45) 
email varchar(45) 
phone varchar(45) 
category varchar(45) 
date datetime 
pin int
----------------***************************---------------------
