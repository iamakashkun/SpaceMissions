# SpaceMissions
Explore a comprehensive dataset covering space missions spanning from 1957 to August 2022. This rich dataset provides intricate insights into launch locations, dates, outcomes, responsible companies, and detailed specifications of the rockets used, including names, prices, and statuses.

I. Introduction:
Brief Overview of the Dataset: This dataset covers space missions from 1957 to August 2022, detailing launch locations, dates, mission outcomes, responsible companies, and rocket specifics like names, prices, and statuses.
Purpose of Analysis: This analysis aims to explore trends, mission success rates, country comparisons, popular rockets, and launch locations within the dataset. Key goals include investigating launch frequency patterns, and success rates over time, identifying countries with consistent mission success, determining frequently used rockets, and analyzing geographical launch patterns. This analysis provides valuable insights into the historical and current landscape of space missions.

II. Data Transformation:
Data Cleaning: To ensure data integrity, the first step involved promoting headers for clear column identification. Rows with blank values were filtered out, eliminating inconsistencies. Handling missing values improved dataset reliability. Additionally, duplicates were removed, preventing redundancy and maintaining accuracy.

![image](https://github.com/iamakashkun/SpaceMissions/assets/148537108/d1ff51e5-77ff-40d1-b349-c1b6491585ad)
(Preview of raw data)

Data Transformation: In the Power Query Editor, data underwent a significant transformation. Data types were meticulously adjusted, ensuring proper alignment with analytical needs. Basic calculations were performed, specifically computing mission cost prices. Calculated fields were created to enhance analytical depth. Furthermore, relationships were established in the Model View of Power BI, providing a cohesive structure for seamless cross-variable analysis. These transformations ensured a clean, coherent dataset ready for in-depth analysis.


![image](https://github.com/iamakashkun/SpaceMissions/assets/148537108/2cf83ee7-336d-4763-b249-1cbc527eed1e), ![image](https://github.com/iamakashkun/SpaceMissions/assets/148537108/d0a119d1-ce1a-419a-b5ed-3e4dc30d709b)


III. Data Analysis:


![image](https://github.com/iamakashkun/SpaceMissions/assets/148537108/a46a359e-3957-49f1-b38d-8344f2f81f2b)


Rocket Launch Trends: Analyzing the dataset of 1265 missions, rocket launches exhibited a significant upward trend over time. Visualized through intuitive line charts, this trend showcased the increasing frequency of space missions, capturing the industry's progressive momentum.
Mission Success Rate: Delving into mission outcomes, the analysis revealed a remarkable success rate of 94.6%. This was complemented by visualizations illustrating the evolution of success rates across different periods. The data was represented graphically, capturing shifts and trends in mission outcomes effectively.
Country-wise Analysis: Comparing success rates across countries provided intriguing insights. CASC led with 233 successful missions, followed closely by SpaceX (170) and NASA (146). Trends over time were analyzed, spotlighting shifts in success rates and identifying emerging spacefaring nations.
Popular Rockets: Exploring rocket usage, Falcon 9 Block 5 emerged as the workhorse, contributing to 111 successful missions. Additionally, Ariane 5 ECA played a pivotal role in 80 missions. Analysis extended to the operational status of these rockets, offering valuable context to mission planners and enthusiasts.
Launch Location Patterns: Geographical analysis revealed two primary launch hubs. The Kennedy Space Center, with 146 missions and an investment of 53.60 billion USD, stood out as a key launch location. Guiana Space Center, hosting 81 missions with an investment of 16.17 billion USD, showcased a robust space launch program. Visualized through maps and geographical representations, these patterns underscored strategic launch site selection and investment distribution.
This comprehensive data analysis not only illuminated historical trends but also provided a strategic lens for future space missions, offering actionable insights for industry stakeholders and enthusiasts alike.

IV. Tools and Methodology:
Tools Used: For this analysis, Microsoft Power BI was the primary tool employed for data analysis and visualization. Its selection was based on its robust features and interactive capabilities, allowing for in-depth exploration of the space mission dataset. Power BI's intuitive interface and powerful visualization options facilitated comprehensive insights into the data, ensuring a detailed and visually engaging presentation of the findings.
Methodology: The methodology adopted for this analysis followed a systematic approach, ensuring the accuracy and relevance of the insights derived:
1.	Data Cleaning: The raw dataset was meticulously cleaned to eliminate inconsistencies. Steps included handling missing values, removing duplicates, and ensuring data consistency. This process laid the foundation for reliable analysis.
2.	Data Transformation: Transformation in Power Query Editor included adjusting data types, creating calculated fields, and aggregating variables. Specific calculations were performed, including mission cost analysis, to enhance the dataset's analytical depth.
3.	Visualization Techniques: Various visualization types were utilized for each analysis aspect. Line charts and time series analysis were employed to depict rocket launch trends. Success rates were visualized using appropriate charts, emphasizing trends and fluctuations—country-wise analysis utilized bar charts for easy comparison. Rocket popularity and launch location patterns were showcased using interactive maps and geographical visualizations, offering a clear understanding of the data's geographical aspects.
4.	Interactivity: Power BI's interactive features were leveraged to create dashboards and reports allowing users to drill down into specific data points. Filters, slicers, and dynamic visuals were utilized to enhance user engagement and facilitate focused exploration.
This methodology ensured a structured and comprehensive approach to analyzing the space mission dataset. By emphasizing data cleaning, transformation, and specific visualizations tailored to each analysis aspect, the insights derived were not only accurate but also presented in an accessible and visually appealing manner, enabling stakeholders to grasp the nuances of the space mission data effortlessly.

V. Conclusion and Recommendations:
Conclusion: In conclusion, the analysis of space mission data spanning from 1957 to August 2022 has unearthed compelling insights. Rocket launches have demonstrated a consistent upward trend, reflecting the industry's continuous growth and technological advancements. The remarkably high mission success rate of 94.6% underscores the industry's reliability and expertise in executing space missions. Noteworthy spacefaring entities like CASC, SpaceX, and NASA have consistently excelled, with SpaceX challenging traditional norms by becoming a frontrunner. The popularity of rockets like Falcon 9 Block 5 and Ariane 5 ECA highlights their enduring reliability. Geographically, launch location patterns emphasize the strategic considerations that influence site selection, indicating the complexities of global partnerships and geopolitical factors.
Significance of the Trends: These trends signify a robust and dynamic space industry, driven by innovation, collaboration, and strategic decision-making. The high success rates indicate the industry's maturity and adherence to rigorous standards. The rise of private companies suggests a shift in the traditional space landscape, with increased competition fostering innovation and efficiency. Geopolitical and strategic factors continue to play a pivotal role in launch location choices, reflecting the industry's multifaceted nature.

Recommendations: Based on the analysis, the following recommendations are proposed:
1.	Continuous Monitoring and Collaboration: Space agencies and companies should continue to collaborate and share knowledge to enhance the industry's collective expertise. Monitoring trends and learning from successes and failures remain crucial for growth.
2.	Investment in Emerging Technologies: Continued investment in emerging technologies, such as reusable rocket components and advanced propulsion systems, can further enhance efficiency and reduce costs, contributing to sustainable space exploration.
3.	Focus on Sustainability: Implementing eco-friendly practices in rocket manufacturing and launch processes can mitigate environmental impact, aligning the industry with global sustainability goals.
4.	Global Collaboration: Encouraging international collaboration in space endeavours can foster peaceful coexistence and knowledge sharing, contributing to advancements in space science and exploration.
5.	Educational Initiatives: Investing in STEM (Science, Technology, Engineering, and Mathematics) education can nurture the next generation of space scientists and engineers, ensuring a skilled workforce for future space missions.
6.	Research on Space Debris Management: With the increase in space activities, research on effective space debris management strategies is essential to maintain a clutter-free space environment.
By heeding these recommendations, the space industry can continue its upward trajectory, fostering innovation, collaboration, and sustainability, thus shaping a promising future for space exploration.

VI. Acknowledgements and References:
Acknowledgements: I extend my gratitude to Maven Analytics for providing the invaluable dataset used in this analysis. Their commitment to open data access enables meaningful explorations and insights within the data analytics community.

I also acknowledge the data provided by NextSpaceFlight (https://nextspaceflight.com/), which contributed to enriching the analysis and findings.

References:
The analysis utilized data sourced from Maven Analytics' Data Playground, accessible at: https://www.mavenanalytics.io/data-playground. This dataset formed the foundation of my research and findings, ensuring the accuracy and integrity of my analysis. Data from NextSpaceFlight (https://nextspaceflight.com/) was also utilized to enhance the depth of the analysis.
