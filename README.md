# HR-Analytics


Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

<img src="https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/09/wns_hack_im_1.jpg">

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

 
<h4>Dataset Description</h4>

Variable	Definition<br>
employee_id-	Unique ID for employee<br>
department-	Department of employee<br>
region-	Region of employment (unordered)<br>
education-	Education Level<br>
gender-	Gender of Employee<br>
recruitment_channe- Channel of recruitment for employee<br>
no_of_trainings- no of other trainings completed in previous year on soft skills, technical skills etc.<br>
age-	Age of Employee<br>
previous_year_rating-	Employee Rating for the previous year<br>
length_of_service-	Length of service in years<br>
KPIs_met - >80%	if Percent of KPIs(Key performance Indicators) >80% then 1 else <br>
awards_won?-	if awards won during previous year then 1 else 0<br>
avg_training_score-	Average score in current training evaluations<br>
is_promoted	(Target)- Recommended for promotion
 
<h4>Evaluation Metric</h4>
The evaluation metric for this competition is F1 Score.

 
