#  Overview

This project is an interactive Power BI dashboard created to analyze online learning platforms and courses.
The dashboard provides insights into course popularity, student distribution, instructor ratings, and language preferences.


By combining data cleaning, DAX calculations, and visualization best practices, this project demonstrates how Power BI can turn raw tabular data into insightful dashboards that support decision making.

# Dataset


Source: A web-scraped dataset (originally collected by another contributor from an online learning platform).

Nature of Data: Contains course-related information such as course title, category, sub-category, language, number of viewers, ratings, and instructor details.

Preprocessing Done:

Cleaned missing/duplicate records

Standardized category & language fields

Created calculated measures using DAX 

*Since the dataset was web-scraped by a third party, it is used here purely for educational and project demonstration purposes*


# Problem Statements

1.Examine the distribution of course types across categories to uncover trends and insights, enabling the client to strategically determine which course types to launch in specific categories for maximum impact and alignment with learner demand, also count the number of courses by category and sub-category.


2.Calculate the average number of views for each category, sub-category, and language to provide insights into viewer engagement patterns and inform strategic content development.


3.Identify the most commonly taught skills in today's educational landscape based on the data given based on category to ensure course offerings remain relevant and aligned with current job market demands.


4.What is the distribution of various Languages  in which a particular course is  created?


5.Determine the language preferences for each category based on viewer preferences, so that clients can optimise course accessibility and better align content with audience demand. Clients only want to analyse this data for the top 5 categories based on user preferences.


6.Investigate the relationship between the availability of subtitles and the number of views for courses to determine how subtitle options may impact viewer engagement and accessibility.


7.Identify the top three instructors for each category and subcategory based on ratings   to highlight educators who consistently deliver high-quality content and effectively engage learners so that they can be approached by your client to make content for them and make this visual as static.


8.Examine the relationship between course duration and the number of views to understand how the length of a course may influence viewer engagement and preferences for each category and sub-category, if course duration has a month (in each month only 60 hours of content ) and for flexible schedules make the timing as 200 hours.


9.In the context of recorded lectures, we need to investigate whether the variety of skills offered within each category and subcategory has a measurable impact on viewership

# Dashboard preview

(photo)

# Key Insights

📌 Data Science and Computer Science dominate enrollments, followed by Business and Arts & Humanities.

📌 Courses with multiple subtitle languages attract significantly more students compared to single language courses.

📌 English is the most prominent course language (≈30%), followed by Spanish, French, and Japanese.

📌 Courses in the 60–80 hour range tend to balance high viewership with meaningful learning duration.

📌 Several instructors (e.g., Douglas C. Mo., Jason Roy, Raquel Prado) maintain ratings above 4.0, showing consistent quality.

📌 Sub-categories like Social Sciences, Machine Learning, and Probability & Statistics show strong demand in terms of skills and course count.

 
 


