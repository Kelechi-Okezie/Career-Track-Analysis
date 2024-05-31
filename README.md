# Career-Track-Analysis
One of the functionalities the 365 company introduced in a 2021 platform release included the option for student enrollment in a career track. The tracks represent an ordinal sequence of courses that eventually lead to obtaining the skills for one of three job titles: data scientist, data analyst, or business analyst.

Completing a career track on the platform is a challenging task. To acquire a corresponding career certificate, a student must pass nine course exams (seven compulsory and two elective courses) and sit for a career track exam encompassing topics from all seven required courses.

In this Career Track Analysis with SQL and Tableau project, I am tasked with analyzing the career track enrollments and achievements of 365’s students. I’ll first need to retrieve the necessary information from an SQL database. Afterward, I’ll feed this information to Tableau, visualize the results, and finally interpret them.

## What is the number of enrolled students monthly? Which is the month with the most enrollments? Speculate about the reason for the increased numbers.
 Let’s study the combo chart, showing the number of monthly career track enrollments and the fraction of students who complete the track—not necessarily within the month of enrollment.

![image](https://github.com/Kelechi-Okezie/Career-Track-Analysis/assets/141277019/c6275453-a260-4b84-a7af-1bfdfcdb749b)


Studying the height of the bars, we observe a fluctuating number of people enrolling monthly (roughly 800 and 1,200), with August registering a higher number. The reason is a campaign that 365 ran for three days which gave all its students free access to the platform. We can see that this has both boosted the number of enrollments and, as a result, the completion rate. Still, most people enrolled in this period seem to have started the track but have given up once the free days ended.

## Which career track do students enroll most in?
When considering the number of enrolled students per track, the data analyst career track is the most sought after among 365 students, followed by the data science track and, finally, the business analyst one.

![image](https://github.com/Kelechi-Okezie/Career-Track-Analysis/assets/141277019/8168ff2c-c8fe-49d2-bccb-48d5b9d7999b)


## What is the career track completion rate? Can you say if it’s increasing, decreasing, or staying constant with time?
Studying the line part of the combo chart, we see the numbers fluctuating. But the passing rate (around 2%) is relatively low, with numbers varying between tracks. Therefore, it’s difficult to state any dependency with time—i.e., we can’t conclude with certainty the completion rate increases, decreases, or stays constant.

![image](https://github.com/Kelechi-Okezie/Career-Track-Analysis/assets/141277019/f2a9c278-79e1-4842-8ffc-bfae8c2b69e3)


## How long does it typically take students to complete a career track? What type of subscription is most suitable for students who aim to complete a career track: monthly, quarterly, or annual?
We can argue, that students need a lot of time to complete an entire career track. This claim is supported by the second bar chart created in the project, where we’ve seen that it takes students an annual subscription to complete a single career track.

![image](https://github.com/Kelechi-Okezie/Career-Track-Analysis/assets/141277019/1fcc447c-3a30-4708-87b1-2e1d58739699)


Such an analysis should therefore be conducted for long periods. The SQL database shows that the last completion date recorded is May 16, 2023. If we assume that it takes roughly a year for students to complete a track, then people registered towards the end of the period under analysis have yet to complete theirs.

## What advice and suggestions for improvement would you give the 365 team to boost engagement, increase the track completion rate, and motivate students to learn more consistently? 
Given the relatively low success rate of 2% in completing a career track, we can appreciate how much effort, engagement, and persistence it requires to complete one. Students need to complete nine courses, pass nine course exams, and the career track itself—encompassing topics from all seven compulsory courses entering the track. We understand that this can make students feel overwhelmed and discouraged.

The 365 team should put effort into engaging their students and helping them reach their goals. They could launch a gamified version of the platform, which allows for maintaining streaks and, as a reward, claiming great prizes. Students should be encouraged to participate in a News Feed option of the platform, share their thoughts and learning progress, and seek help from instructors and fellow students in a Q&A hub.
