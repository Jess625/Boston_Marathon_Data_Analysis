## 🏃‍🏃‍ Goals of Project:
* Clean and join three separate datasets (2015, 2016 and 2017 results respectively)
* Explore Data / Understand Trends
    * Average finishing times year over year
    * Distributions of finishing times by year and gender
    * Total number of runners broken down by year, gender and International vs American
    * Average finish time by age and gender
    * Avg 5K split pace (where are runners generally slowing down?) against elevation graph of race course

See full Notebook File Here: https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Boston_Marathon_Data_Exploration.ipynb
<br />
NOTE: ** If Github is not rendering notebook, please see full notebook here: https://nbviewer.jupyter.org/github/Jess625/Boston_Marathon_Data_Analysis/blob/main/Boston_Marathon_Data_Exploration.ipynb
Data set:<br />
https://www.kaggle.com/rojour/boston-results <br />


## Findings:
![Figure 1](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Finishing_times_yoy.png)
![Figure 2](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Fininshing_times_year_gender.png)

* The largest percentage of runners across all years finish in the 3:24:27 and 3:49:30 window
* Nearly all runners finish in under 6:20:00
* 2015 runners skewed fastest out of all three years
    * Interesting to look at weather of all three years:
        * April 20, 2015: Overcast with a high of 45F
        * April 18, 2016: Scattered clouds with a high of 66F
        * April 17, 2017: Scattered clouds with a high of 73F

![Figure 3](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Runner_counts_yoy.png)

* Runner counts remained stable YoY, with women making up around 45% of all runners
* The number of American vs International runners is fairly stable YoY, with the number of International runners trending slightly upward each year

![Figure 4](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Age_count_avg_finish.png)
![Figure 5](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Age_count_avg_finish_gender.png)

* The largest number of runners are between ages 30 and 50
* Age and finishing time are postively correllated with time generally increasing with age
* This data suggests that men may peak earlier than women, with the fastest average finishing age for men at 23 and for women at 34

![Figure 6](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Avg_splits_5K_segment.png)
![Figure 7](https://github.com/Jess625/Boston_Marathon_Data_Analysis/blob/main/Avg_course_eleveation_mile.png)

* Overall, runner splits trend slower as the race progresses with the slowest splits appearing between 30K and 35K of the race, followed by a slight decrease in pace during the final 7K of the race
* Since the elevation of the race course largely decreases up until mile 16, it would be reasonable to believe that pace may stay steady or even decrease during this portion of the race, however, we see that race splits increase and peak during the 30K to 35K split, which coincides with the largest elevation gain segment of the course
    * The data suggests that the fatigue of running many miles combined with the sudden elevation gain of the 30K to 35K segment may result in a runner's slowest mile splits
