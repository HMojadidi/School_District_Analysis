# School_District_Analysis

# School District Analysis Report

## Overview of Project
The school board has previously assigned my team to analyze data from the district's high schools to find trends in reading, math and overall passing percentages based on factors such as school spending per student, school size and school type. My team and I put together this data. Later we were informed that there may have been some academic dishonesty with the ninth grade math and reading scores of Thomas High School. The school board asked that we not use that particular data but still keep the rest of the data intact. 

### Purpose
The purpose of the Module 4 Challenge is to replace the ninth grade math and reading scores data from Thomas High School with Nan. After updating the data, we are then asked to compile a new analysis, based on the new data, of the reading, math and overall passing percentages based on these factors: school spending per student, school size and school type. 

## Analysis and Challenges

### Deliverable #1: 

I used the Pandas loc method to retrieve the ninth-grade reading and math scores for Thomas High School, Then, using the Pandas NumPy module, I changed the reading and math scores to Nan:

![Nan inserted for ninth-graders at THS](https://user-images.githubusercontent.com/95712234/159373688-b0f8b111-163d-47b2-bedc-9a1b4805ce65.png)

### Deliverable #2:

Using the newly modified data, I repeated the school district analysis. In comparing the results from the previous analysis to the current one, one can see the following results:

#### District Summary:

For the district summaries, after adjusting the data, the data is mostly unaffected. The slight drop in the math passing percentage is almost neglible.

![New District Summary](https://user-images.githubusercontent.com/95712234/159374182-7ef77478-fa88-4b8f-8721-d8ed39bb2f12.png)

![Previous District Summary](https://user-images.githubusercontent.com/95712234/159374188-1da3d20b-0408-4917-9f51-333d029b4054.png)

#### School Summary:

![New per_school_summary](https://user-images.githubusercontent.com/95712234/159374586-e6b14da0-b5b0-45cf-a57b-f8fa0dc27d14.png)

![Previous per_school_summary](https://user-images.githubusercontent.com/95712234/159374598-27ebe50a-3e7f-443f-8fba-597a3634d21a.png)

For the school summary, although the average math and reading scores were rather unaffected, the overall passing percentages for math and reading were deeply affected after the adjusted calculations. This is reflective of calculations based on the total student body count while getting percentages, and yet the entire ninth grade was excluded.

#### Top 5 schools:
![Revised top 5 schools](https://user-images.githubusercontent.com/95712234/159380117-55e27760-be90-4287-945e-7dfc52e279e7.png)

![Previous Top 5 schools](https://user-images.githubusercontent.com/95712234/159380137-bb522c74-46ec-40c1-a3e1-ad1916db49e2.png)

Upon reviewing the ranking of top 5 schools, the results for Thomas High School remains unaffected.


## Results
The written analysis has the following:

Overview of the school district analysis:

The purpose of this analysis is well defined (3 pt).
Results:

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
