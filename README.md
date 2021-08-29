# School District Analysis Challenge 
## Project Overview

1. Replace ninth-grade reading and math scores for Thomas High School 
2. District Summary
3. School Summary
4. Top 5 and Bottom 5 performing school based on overall passing rate
5. Average math score for each grade level for each school
6. Average reading score for each grade level for each school
7. Scores by school spending per student, by school size, and by school type

In addition to Original Module tasks:
1. Open Jupyter Notebook files from local directories using a development environment.
2. Read an external CSV file into a DataFrame.
3. Format a DataFrame column.
4. Determine data types of row values in a DataFrame.
5. Retrieve data from specific columns of a DataFrame.
6. Merge, filter, slice, and sort a DataFrame.
7. Apply the groupby() function to a DataFrame.
8. Use multiple methods to perform a function on a DataFrame.
9. Perform mathematical calculations on columns of a DataFrame or Series.

## Purpose of Analysis
Maria, a chief data analyst for a specific school district has reached out for help to analyze data on student's math and reading standardized test scores. Once this data is gathered and cleaned, it will be correlated to how much each school spends per student in the district. After initial analysis of the data recieved, new information is given that implies academic dishonest among one school's, Thomas High School, ninth grade scores. In order to give a fair and accurate read to all schools in the district, the scores from Thomas High School's ninth grade class must be replaced as "not a number", or "NaNs," before the data is run again. Once the process is completed, it can be determined whether the math and reading scores from the nineth grade class at Thomas High School have grossly skewed the data. 

## Resources
* Data source: schools_complete.csv, students_complete.csv
* Software: Python 3.7.6, Anaconda, Conda, Jupyter-Notebook, Pandas, Numpy, GitBash 

## Results
The bullets below will show how each of the seven school distrit metrics that were studied have been affected by the changes in data due to the removal of the Thomas High Scool nineth grade scores.

* Affects on District Summary
Data from Original Analysis:
![Original District Summary](https://user-images.githubusercontent.com/88064181/131235171-ce35b004-59f7-4f45-9285-ced25b48a3be.png)

Data from Adapted Analysis: 
![Adjusted District Summary ](https://user-images.githubusercontent.com/88064181/131235173-7765268f-48d2-441e-9440-dbb14270c32d.png)

Overall, the data for the district saw nominal changes when the test scores from about 400 students was removed from the overall data set. The overall passing percentage dropped by less then one point, and the passing math and reading scores dropped by hundreths of a percentage point. 

* Affects on School Summary
Data from Original Analysis:
![Original School Summary](https://user-images.githubusercontent.com/88064181/131235175-c37b52a3-5be2-4bb0-8c84-b19dbfe8db77.png)

Data from Adapted Analysis: 
![Adjusted School Summary](https://user-images.githubusercontent.com/88064181/131235179-17664b96-3d72-4f22-8e94-75d267569fb2.png)

When comparing the original data to the adjusted data with the removal of about 400 students from Thomas High School, the high school saw a huge affect on its numbers. It's overall passing percentage dropped from about 91% to about 65%. 

* Affects on Thomas High School Ranking 
Data from Original Analysis
![Original School Ranking](https://user-images.githubusercontent.com/88064181/131235186-341703ab-efdf-4f5a-bc8a-1fab9512bbc6.png)

Data from Adapted Analysis
![Adjusted School Rankings](https://user-images.githubusercontent.com/88064181/131235191-f6d7c79e-0768-41a7-ac4f-e9f2197adcf2.png)

As shown above, Thomas High school was originally second from the top of the school rankings, but after adjusting the scores, they are in the middle of the rankings at eighth place.

* Affects on Math and Reading Scores by Grade

Data from Original Analysis
![Original Reading Scores by Grade](https://user-images.githubusercontent.com/88064181/131235193-9e9f357f-1b83-45cb-9948-bff20f609982.png)
![Original Math Scores by Grade](https://user-images.githubusercontent.com/88064181/131235195-91ba5990-734e-4208-9968-b9933e904fad.png)

Data from Adapted Analysis

![Adjusted Reading Scores by Grade](https://user-images.githubusercontent.com/88064181/131235197-62e9a244-ea45-45d9-835e-40227ddd4ca3.png)
![Adjusted Match Scores by Grade](https://user-images.githubusercontent.com/88064181/131235201-ad566379-e857-4c04-9fd9-21da1ff6decc.png)

With the adjusted scores, the entire math and reading scores for Thomas High School's nineth graders is comppletely removed. 

* Affects on Scores by School Spending
Data from Original Analysis
![Original Spending Scores](https://user-images.githubusercontent.com/88064181/131235216-d3396fe1-4ec9-405c-848d-26a078d19d4a.png)

Data from Adapted Analysis
![Adjusted Spending Scores](https://user-images.githubusercontent.com/88064181/131235218-5bbbf0de-1b88-4cee-9d51-6fddbc1aa085.png)

The school spending data comes from a much larger data pool because it includes all students across all grades within the district. While the mid-budget schools that include Thomas High School did see a drop in their scores, the difference was minimal. 

* Affects on Scores by School Size
Data from Original Analysis
![Original School Size Scores](https://user-images.githubusercontent.com/88064181/131235220-6707ef61-2ff0-4e8e-9a1f-8671efb070b3.png)

Data from Adapted Analysis
![Adjusted School Size Scores](https://user-images.githubusercontent.com/88064181/131235224-31edf90f-dcf1-46fa-8209-a5aacea10515.png)

The school size data comes from a much larger data pool because it includes all students across all grades within the district. While the mid-sized schools that include Thomas High School did see a drop in their scores, the difference was minimal. 
 
* Affects on Scores by School Type
Data from Original Analysis
![Original School Type Scores](https://user-images.githubusercontent.com/88064181/131235226-8c1a5d9d-19df-4594-894e-764ce2d4b5e8.png)

Data from Adapted Analysis
![Adjusted School Type Scores](https://user-images.githubusercontent.com/88064181/131235229-a8563b91-68e3-4847-b279-5b2367c86d15.png)

The school type data comes from a much larger data pool because it includes all students across all grades within the district. While the charter school data that include Thomas High School did see a drop in their scores, the difference was not impacted severly by the removal of the nineth grade scores. 

## School Data Summary
By replacing the scores from Thomas High School's nineth grade class, there has been a drastic change in the results, especially pertaining to Thomas High School. By obsoleting about 400 grades, as postulated from the 1635 total student population of Thomas High School, we can re-analyze the data and see what specific results were affected.  

In the original data, Thomas High School students were passing the standardized test overall at an average of ~91%. One the nineth grade scores were replaced with NaNs, Thomas High School saw their average drop to ~65%. 

The original data ranked Thomas High School as second overall amongst the fifteen schools in the district. Once the nineth grade class was taken out of the equation, the high school dropped to eigth place overall. It seems that, if the nineth graders did in fact receive the original scores that had been presented, they really gave the school a boost and helped carry the suffering elder-classmen. 

The Thomas High School nineth graders, according to the original data, were tied in a second place ranking, putting them at the top of their grade level. With the scores being scratched out, the Thomas High School nineth graders are no longer able to be compared to their fellow students. It basically disqualifies the nineth graders from any such ranking. 

Besides directly impacting the rankings and results for Thomas High School, and subsequently giving other schools in the district a boost, the overall passing rates, averages, and scores were all affected. Overall, Charter schools saw a slight, but not insignificant, drop in their overall passing percentages. Thomas High School was considered a medium size school, so the scores that were used in comparing school sizes also saw a slight change. 

Overall, while recording the nineth grade test scores from Thomas High school as non-numbers greatly affected the ranking of Thomas High School itself, this change in data had very slight affects on the larger data fields. Scores and rankings that were compared on the school vs school level saw great impact, and other schools shifted around in the rankings to accomodate the drop in Thomas High School's passing scores. The big picture data, including the scores based on school size, school type, and school spending saw a less significant impact. Because these data fields were drawing from a larger pool of data, the small, in comparison, change to the nineth grader's scores made little overall impact. 


