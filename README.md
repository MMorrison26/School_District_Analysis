# School District Analysis
## *Overview*
The Chief Data Scientist for a city school district, Maria, needs to analyze the standardized testing results in the district to present and identify trends. The School Board and Superintendent would also like a breakdown on school funding among the district. After hearing of potential "academic dishonesty," they also requested a synopsis showing how the data would be affected if we specifically removed scores from the 9th graders at Thomas High School. They will use all of this analysis to make decisions regarding the upcoming school year moving forward. 
## *Results*
Based upon our results before and after removing Thomas HS 9th graders, here is what we found:
* Given the size of the data, the swap in THS scores hardly affected the overall district summary - just slightly higher.
* The school summary is pretty telling because Thomas High School goes from only 65% passing up to 91% passing overall.
  * Before Replacing: \n
  ![image](https://user-images.githubusercontent.com/87578449/133528408-58cb7eb6-752d-4539-879c-0f6a1defe6b5.png)

  * After Replacing:\n
  ![image](https://user-images.githubusercontent.com/87578449/133528372-da541730-5765-48ea-b8f3-6738190edc08.png)

* Replacing the 9th graders' math/reading scores brings Thomas HS up to #2 in the overall rankings.
![image](https://user-images.githubusercontent.com/87578449/133527489-c241dee0-f705-45cb-a65d-13c4904ad46e.png)

* Replacing the 9th graders' scores also affects the following:
  * Scores by grade: 9th graders increased scores overall, but 10th-12th grade was not affected.
  * Scores by school spending: this slightly affected the $630-$644 bucket (which THS was in).
  * Scores by school size: Again, the Medium schools (where THS was) were affected positively.
  * Scores by school type: Because this was so aggregated, the Charter school type was only slightly affected.
## *Summary*
The biggest change could be seen specifically for the line item of Thomas High School in the overally summary, which was a 26% swing. Because there were over 39,000 rows of data contributing to the aggregated results, the 9th graders' poor passing results from Thomas HS didn't have as much of an effect as we might have originally thought. Only making changing to Thomas HS means that the categories their school fell into were positively affected (fairly or unfairly): Charter, Medium, $630-$644 budgeting. It would appear that there was no academic dishonesty given that their scores *increased* instead of *decreased* when we removed the alleged "incriminating" data. However, we would need more details moving forward to come to a more clear conclusion.

In all, we wish all the schools and educators the best of luck in the coming school year!
