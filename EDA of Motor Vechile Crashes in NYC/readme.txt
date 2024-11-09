The columns in this dataset.
#   Column                      Dtype  
---  ------                      -----  
 0   crash_date                  object 
 1   crash_time                  object 
 2   borough                     object 
 3   zipcode                     object 
 4   latitude                    float64
 5   longitude                   float64
 6   location                    object 
 7   on_street_name              object 
 8   cross_street_name           object 
 9   off_street_name             object 
 10  no_of_persons_injured       float64
 11  no_of_persons_killed        float64
 12  no_of_pedestrians_injured   int64  
 13  no_of_perdestrians_killed   int64  
 14  no_of_cyclist_injured       int64  
 15  no_of_cyclist_killed        int64  
 16  no_of_motorist_injured      int64  
 17  no_of_motorist_killed       int64  
 18  contributing_factor_vech_1  object 
 19  contributing_factor_vech_2  object 
 20  contributing_factor_vech_3  object 
 21  contributing_factor_vech_4  object 
 22  contributing_factor_vech_5  object 
 23  collission_id               int64  
 24  vech_type_code_1            object 
 25  vech_type_code_2            object 
 26  vech_type_code_3            object 
 27  vech_type_code_4            object 
 28  vech_type_code_5            object 

There was more than 2 million records in this dataset. This dataset had records for last 10 years.
As this was a huge dataset, i filtered the data from 2020 to 2023.
I only did EDA and NULL Value treatment.

_percentage of Null Values in each column.
crash_date                     0.000000
crash_time                     0.000000
borough                       31.093554
zipcode                       31.105804
latitude                      11.232876
longitude                     11.232876
location                      11.232876
on_street_name                21.423751
cross_street_name             38.126979
off_street_name               82.911764
no_of_persons_injured          0.000845
no_of_persons_killed           0.001455
no_of_pedestrians_injured      0.000000
no_of_perdestrians_killed      0.000000
no_of_cyclist_injured          0.000000
no_of_cyclist_killed           0.000000
no_of_motorist_injured         0.000000
no_of_motorist_killed          0.000000
contributing_factor_vech_1     0.336241
contributing_factor_vech_2    15.689248
contributing_factor_vech_3    92.809484
contributing_factor_vech_4    98.366573
contributing_factor_vech_5    99.555386
collission_id                  0.000000
vech_type_code_1               0.682762
vech_type_code_2              19.466426
vech_type_code_3              93.078561
vech_type_code_4              98.424725
vech_type_code_5              99.569091

After NULL Value Treatment:
crash_date                    0
crash_time                    0
borough                       0
latitude                      0
longitude                     0
on_street_name                0
cross_street_name             0
no_of_persons_injured         0
no_of_persons_killed          0
no_of_pedestrians_injured     0
no_of_perdestrians_killed     0
no_of_cyclist_injured         0
no_of_cyclist_killed          0
no_of_motorist_injured        0
no_of_motorist_killed         0
contributing_factor_vech_1    0
contributing_factor_vech_2    0
collission_id                 0
vech_type_code_1              0
vech_type_code_2              0
Year                          0
Month                         0
no_of_total_affected          0
dtype: int64
