Grad-Chat Mentorship Analysis Dashboard
Project Overview
This project is a Power BI dashboard created to analyze mentorship engagement in a college setting, focusing on junior-senior connections within the Grad-Chat mobile app. Grad-Chat is designed to connect juniors seeking guidance with senior mentors, fostering a supportive learning environment. This dashboard visualizes data related to mentorship engagement levels, mentorship areas, and feedback scores, providing insights to enhance the mentoring experience.

Problem Statement
The goal of this dashboard is to:

Understand which mentorship areas (e.g., Placement, Study Tips) are most active.
Analyze the engagement levels (Low, Medium, High) across different mentorship areas.
Identify areas with high feedback scores, indicating successful mentoring sessions.
Provide actionable insights into the areas where junior students seek the most help and evaluate the effectiveness of senior mentors in those areas.
Key Visuals
CountSessionsByEngagement by Engagement Level: Bar chart showing the distribution of session counts across engagement levels.
HighEngagementPercentage and CountSessionsByEngagement by Mentorship Area: Combined chart comparing the percentage of high engagement with the total session count for each mentorship area.
TotalSessionsByArea by Mentorship Area: Bar chart showing the total number of sessions conducted in each mentorship area.
High Engagement Percentage: A card visual displaying the overall percentage of sessions with high engagement.
Average Feedback Score by Mentorship Area: Bar chart and pie chart providing a breakdown of feedback scores by mentorship area.
Table of High-Feedback Sessions Count by Mentorship Area: Table highlighting mentorship areas with high feedback counts.
Data Sources
The dashboard uses the following fields from the Junior_Senior_Connections dataset:

Mentorship_Area: Categories like Career Guidance, Placement, Study Tips, and Event Management.
Engagement_Level: Indicates session engagement levels (High, Medium, Low).
Session_Count: Number of sessions held within each mentorship area.
Feedback_Score: Feedback score from juniors, reflecting session quality.
Calculations
Several DAX measures were created to support the analysis:

CountSessionsByEngagement: Total number of sessions by engagement level.
HighEngagementSessions: Count of sessions with “High” engagement.
HighEngagementPercentage: Percentage of sessions with high engagement.
TotalSessionsByArea: Total session count by mentorship area.
AverageFeedbackScoreByArea: Average feedback score per mentorship area.
HighFeedbackSessionsCount: Count of high-feedback sessions (e.g., scores 4 and above).
How to Use the Dashboard
Slicers: Use the slicers on the right side to filter by engagement level or mentorship area.
Charts: Explore the bar charts and pie chart to analyze session distribution, engagement levels, and feedback scores across different mentorship areas.
Tables: The table displays engagement data for each senior, providing a detailed view of mentor performance.
Insights
The dashboard reveals which mentorship areas have the most engagement and highest feedback scores, helping administrators understand junior needs.
High engagement and positive feedback in certain areas indicate where mentoring efforts are succeeding, while lower scores can highlight areas for improvement.
Future Enhancements
Drill-Throughs: Enable drill-throughs for deeper analysis on individual mentors or specific session details.
Trend Analysis: Incorporate a time-based analysis to track mentorship trends over different semesters or academic years.
Automated Reporting: Set up scheduled refreshes for live data and email reports for stakeholders.