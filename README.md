<h1 align = "center"> Fake Job Posting Prediction </h1>

<br/>

![Job Search](https://s3-ap-southeast-2.amazonaws.com/www.cryptoknowmics.com/crypto/wp-content/uploads/2019/11/jobss.jpg)

<br/>

### Team Name: Data Diggers

Team Members:
1. Uma Sai Madhuri Jetty
2. Sahithi Priya Gutta
3. Ankita Kumari
4. Ashesh Shahi

<br/>

### 1. Project Description and Reasearch Question
- The job market is hard enough to navigate without having to worry about some posting turning out to be a scam—or even just a dead end.
- The project focuses on predicting which job descriptions are fraudulent or real using text data and meta data features.
- Focuses on identifying key traits/features of job descriptions which are fraudulent in nature.
- The main audience of this project will be the students and job- seekers looking for any job opportunities such as: internships, part-   time, full-time jobs.
- The project has a data of 18K job descriptions out of which about 800 are fake.



### 2. Domain and Data: Data understanding 

Job boards can be host to scammers who are looking to defraud victims who are at their most suggestible and vulnerable 
that is, job seekers who are so eager to land a position that they ignore the warning signs that all is not as it seems.
Scammers know that finding a job can be tough. To trick people looking for honest work, scammers advertise where real employers 
and job placement firms do. They also make upbeat promises about your chances of employment, and virtually all of them 
ask you to pay them for their services before you get a job. 
<br> The major targets for the scammers are students. Colleges/Universities always explains the students the red flags regarding the 
employment oppurtunities. Still it is not hundered percent possible to eliminate all the scams or save students from scams all the time.
Therefore, we propose a solution to which helps to identify the fradulent jobs using text and meta data information modelling. <br>

#### a. Source and Size of Data 
The Dataset has data from fake_job_posting.csv downloaded from Kaggle. It's a dataset of 48 MB, owned by Shivam Bansal. There are total 18 columns in the data file.
- job_id - Unique Job ID
- title - The title of the job ad entry.
- location - Geographical location of the job ad.
- department - Corporate department (e.g. sales).
- salary_range - Indicative salary range (e.g. $50,000-$60,000)
- company_profile - A brief company description.
- description - The details description of the job ad.
- requirements - Enlisted requirements for the job opening.
- benefits - Enlisted offered benefits by the employer.
- telecommuting - True for telecommuting positions.
- has_company_logo - True if company logo is present.
- has_questions - True if screening questions are present.
- employment_type - Full-type, Part-time, Contract, etc.
- required_experience - Executive, Entry level, Intern, etc.
- required_education - Doctorate, Master’s Degree, Bachelor, etc.
- industry - Automotive, IT, Health care, Real estate, etc.
- function - Consulting, Engineering, Research, Sales etc.
- fraudulent - target variable - Classification attribute.


### Tentative plan for analysis on GCP


### EDA is useful for:
- Delving into data
- Examining important interrelationships between attributes
- Identifying interesting subsets of the observations
- Develop an initial idea of possible associations amongst the predictors, as well as between the predictors and the target variable.<br>


#### Preprocessing Phase
- In this phase, First we'll try to find out which columns has null values in the dataset.
- Then we will fill the missing values of the columns in the dataset.
- We'll also look for outliers and try to remove them.
- After that we'll check the correlation between the features (columns) to find out the most relevant features for the prediction.<br/>

#### Dashboard for Users and Dashboard for Data Engineers
- We'll create two different dashboards one for our main audience/users i.e students or job-seekers and the other for Data Engineers.
- Dashboard for users will be more simplified and clear so that users would be able to understand it easily.
- Dashboard for Data Engineers 




