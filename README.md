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

##### Revised District Summary:

![New District Summary](https://user-images.githubusercontent.com/95712234/159374182-7ef77478-fa88-4b8f-8721-d8ed39bb2f12.png)


##### Previous District Summary:

![Previous District Summary](https://user-images.githubusercontent.com/95712234/159374188-1da3d20b-0408-4917-9f51-333d029b4054.png)



#### School Summary:

For the school summary, although the average math and reading scores were rather unaffected, the overall passing percentages for math and reading were deeply affected after the adjusted calculations. This is reflective of calculations based on the total student body count while getting percentages, and yet the entire ninth grade was excluded.

##### Revised School Summary:

![New per_school_summary](https://user-images.githubusercontent.com/95712234/159374586-e6b14da0-b5b0-45cf-a57b-f8fa0dc27d14.png)

##### Previous School Summary:

![Previous per_school_summary](https://user-images.githubusercontent.com/95712234/159374598-27ebe50a-3e7f-443f-8fba-597a3634d21a.png)



#### Top 5 ranking schools:

Upon reviewing the ranking of top 5 schools, the results for Thomas High School remains unaffected.

##### Revised Top 5 School rankings:

![Revised top 5 schools](https://user-images.githubusercontent.com/95712234/159380117-55e27760-be90-4287-945e-7dfc52e279e7.png)


##### Previous Top 5 School rankings:

![Previous Top 5 schools](https://user-images.githubusercontent.com/95712234/159380137-bb522c74-46ec-40c1-a3e1-ad1916db49e2.png)



#### Lowest 5 ranking schools:

Upon reviewing the ranking of the bottom 5 ranking schools, the results remained the same with no change.

##### Revised Bottom 5 school rankings:

![New Bottom performing 5 schools](https://user-images.githubusercontent.com/95712234/159381008-e08fe702-daa3-4177-af7f-b25ce99eca9c.png)



##### Previous Top 5 school rankings:

![Previous Bottom performing 5 schools](https://user-images.githubusercontent.com/95712234/159381022-54a8796a-7041-44f5-bbab-07a9ee61ae08.png)



#### Scores by school spending:

When categorized by school spending, I noticed that the percentage of students passing math in the $631 - $645 category dropped in the revised data. Previously it was at 73% but now it is 67%.

##### Revised scores in school spending:

![New performace based on spending summary](https://user-images.githubusercontent.com/95712234/159394850-e9f6165f-25fc-4c33-b1e9-4db87b7af30a.png)


##### Previous scores in school spending:

![Previous performance based on spending summary](https://user-images.githubusercontent.com/95712234/159394866-b643a592-8e23-4b57-999d-2ed7d6dba7c5.png)



#### Scores by school size:

Upon reviewing both data side by side, I noticed that in the medium sized school category, there is a drop in the math passing percentage after the data adjustment. It was previously at 94% but now it is at 88%.

##### Revised scores by school size:

![New school performance based on school size](https://user-images.githubusercontent.com/95712234/159395181-6091856c-b360-444f-a50a-074f5a02f524.png)


##### Previous scores by school size:

![Previous school performance based on school size](https://user-images.githubusercontent.com/95712234/159395144-aa024944-ff89-473a-b460-e7f8a63ff1f3.png)



#### Scores by school type:

##### Revised scores by school type:

![Revised school type performance](https://user-images.githubusercontent.com/95712234/159397720-277dbe36-6f6e-431d-a2a8-b52044b4f51b.png)


##### Previous scores by school type:

![Previous school performance based on school type](https://user-images.githubusercontent.com/95712234/159395379-5830b118-757b-49eb-a79c-488643ff4851.png)




## Results
