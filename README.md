## DS_TRACK_KAMILIMU
### KCSE 2016 DATASET REPORT

There are 13 columns with 21 entries 
COLUMNS:
#   Column  Non-Null Count  Dtype 
---  ------  --------------  ----- 
 0   Gender  21 non-null     object (Categorical Variable)
 1   A       21 non-null     int64 
 2   A-      21 non-null     int64 
 3   B+      21 non-null     int64 
 4   B       21 non-null     int64 
 5   B-      21 non-null     int64 
 6   C+      21 non-null     int64 
 7   C       21 non-null     int64 
 8   C-      21 non-null     int64 
 9   D+      21 non-null     int64 
 10  D       21 non-null     int64 
 11  D-      21 non-null     int64 
 12  E       21 non-null     int64 
 
 ![image](https://user-images.githubusercontent.com/53213609/153720751-42c8185b-efa7-4114-bf12-a288e5c9a25a.png)

## EDA

### Data Quality issues
1.The Gender column contains two kinds of information,year and gender
2.Mispelling in the column Gender
3.Check the summations contained in the ALL column


### Feature creation
1.Creation of the year column
2.Further do groupbys to get the column sum 

### Improving data quality 
1.Change mispellings 
2.Validated the summations and changed any wrong summation



###INSIGHTS 
Total number of ALL students =  1366198  

Total no. of FEMALE students =  667967  

Total no. of MALE students = 698231 (higher)


From the boxplot and barplot,the year 2015 stands out in terms of very high upper scores and fewer low scores  
This is consistent with the high leakage results seen in 2016  
  
The year 2016,saw the significant change from 2015.The high grades are fewer ,and we have more low scores  
The year 2016 had tighter rules on exam cheating and there was a change of leadership in the ministry of education which came with more stringent rules on national exams rollout  




 

