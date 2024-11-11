Data columns (total 10 columns):
 #   Column             Non-Null Count  Dtype  
---  ------             --------------  -----  
 0   avg_monthly_hrs    11399 non-null  int64  
 1   department         10848 non-null  object 
 2   filed_complaint    1660 non-null   float64
 3   last_evaluation    10161 non-null  float64
 4   n_projects         11399 non-null  int64  
 5   recently_promoted  236 non-null    float64
 6   salary             11399 non-null  object 
 7   satisfaction       11260 non-null  float64
 8   status             11399 non-null  object 
 9   tenure             11260 non-null  float64
dtypes: float64(5), int64(2), object(3)
memory usage: 890.7+ KB

In this project I have predicted and analyzed the status of the employee. The Biz Requirement is to predict whether the employee will stay with the company or leave the company based on the available information.
H2O AUTOML Libraries were used to predict.
PyCaret was also use to predict the status.
SweetViz was used for the EDA however i did not delve in to the EDA too much.
