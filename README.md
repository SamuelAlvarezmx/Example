# # Kickstarting with Excel

## Overview of Project
### Purpose
The following analysis was done to spot the opportunities Louis can get looking into the data of Kicksarters related to plays. The analysis purpose is to highlight the relation of successful campaigns with their launch date and funding goals in order to find insights in when is the best time to launch the Louise’s project and the recommended funding she should look after.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
As we can see there is a increasing trend of plays been successful beginning in the 2Q of the year, April. The increased percentage of successful plays last until almost the end of the 3Q, to be more precise, August. During this period we can see that the percentage is above 70% so it is highly recommended to invest during this time of the year to assure having our goal met.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104656920/176547161-8700cbc2-478a-4191-bcfc-62361bc343f8.png)
### Analysis of Outcomes Based on Goals
We should recommend Louis that her goal for the play must be kept under a budget of 20K dollars, because it is clear that beyond that number it is more probable to fail, as we can see in the line chart where the number of fail percentage goes above the line of the successful. So the risk of failing increases above 50% when setting a goal over 20k.
We can also see peeks of success percentage in high goals, however, here we can identify outliers, because the number of projects that searched for that kind of money are the fewer and it is not representative of the whole scenario that we are looking on the other Kickstarter´s plays
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104656920/176547181-56f6e87f-fc01-4422-a996-283792dc9853.png)

### Challenges and Difficulties Encountered
1. When doing the countifs I was doing a lot of typing, I don’t know if what I was doing was correct but I needed to type everything and when I tried to copy the formula I found that there were some errors. Also I needed reading comprehension because when I supposedly finished I looked into the Outcomes by goals and didn’t look similar to the one that was in BCS, then I saw that it was not done the correct way because I had no filtered the play subcategory.
<img width="843" alt="Screen Shot 2022-06-29 at 15 57 28" src="https://user-images.githubusercontent.com/104656920/176546600-38a67ae9-fb81-4a54-a5c4-08ff9179968b.png">

2. Also when doing the pivot table, I found difficult to not show the live data. I was trying to hide it from the very beginning, meaning through the kickstarter data and not from the pivot table. Because I was not being able to find the dropdown for the columns. After looking better I found that it was possible directly from the Pivot tables and therefore my results were shown as the ones that we needed to get.
<img width="843" alt="Screen Shot 2022-06-29 at 15 57 28" src="https://user-images.githubusercontent.com/104656920/176546544-e1b30ec3-1fe5-4806-bdde-be024889177b.png">

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. Louise should release her project during the months of April and May which accroding to the data are the most successful months throughout the year.
  2. Louise needs to avoid the last quarter of the year and also the beginning of the year because is when most of the failed projects started. This might be because people are spending their money in different things because of the holidays.

- What can you conclude about the Outcomes based on Goals?
  1. Louise should set a goal for less than 20k in order to stay in the safe side of the Kickstarters because failing percentage of the kickstarters begin to increase beyond this point.

- What are some limitations of this dataset?
  * One of the difficulties I could find is that the blurbs are not in the same language, so we cannot understand sometimes what the project in the Kickstarter was about.
  * Also, there are a lot of data that may not be useful and needs to be worked with, like the dates in UNIX timestamps. The currency should be the same, because the analysis made were done in different currencies and might change a bit the analysis made.
- What are some other possible tables and/or graphs that we could create?
  * I think it is possible to look how long lasted the time between the launch and deadline in order to see if the shortest or longest might have something in common.
  * Average donations with Success and failure, because this could shine light in how much we should seek to get from our backers and what might the people feel comfortable to give to the project.
