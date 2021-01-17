# School District Analysis

## Project Overview
Maria, the chief data scientist for a school district, tasked the analyst with aggregating student test score data and showcase trends in student performance. The results and summary of this task will be used by the school board and superintendent to make decisions regarding school budgets and spending. 

After some analysis, the school board discovered academic dishonesty amongst 9th graders at Thomas High School (THS). In order to uphold state-testing standards, the analyst has been tasked with replacing 9th grade test scores at THS with NaNs while keeping the rest of the data in tact. Then, the data analyst repeated the analysis to discover the impact of the dishonesty. 


## Resources
- Data Sources: [clean_students_complete.csv](https://github.com/r3ginam/School_District_Analysis/blob/main/Resources/clean_students_complete.csv), [schools_complete.csv](https://github.com/r3ginam/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Software: Python 3.9.1, Jupyter Notebook 6.0.3


## Results
* How is the district summary affected?

![](Resources/District_summary_df_orig.png)

![](Resources/District_summary_df_new.png)

* How is the school summary affected?

![](Resources/school_summary_orig.png)

![](Resources/school_summary_new.png)


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?




* How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    
    
    
    - Scores by school spending
    
     ![](Resources/spending_summary_orig.png)
     ![](Resources/spending_summary_new.png)
    
    - Scores by school size
    
     ![](Resources/size_summary_orig.png)
    
     ![](Resources/size_summary_new.png)
    
    
    - Scores by school type
    
     ![](Resources/type_summary_orig.png)  
     ![](Resources/type_summary_orig.png)


## Summary

[Click here to take a deeper look at the analyst's Jupyter Notebook.](https://github.com/r3ginam/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)
