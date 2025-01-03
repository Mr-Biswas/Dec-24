# Dec-24
Dumped all the tasks that I have completed in December and many more to come. This is my new resolution.
Experience
Volunteer || Technical Content Writer & Team Lead
Pandulipi, Magazine Club of Jalpaiguri Government Engineering College || January 2023 - May 2024

Led a team of 6 Pythonistas (junior team members) to create highly-engaging, beginner-friendly content for technical audiences, including the most-viewed article: "Code for the Champions".

Code for the Champions became the top-performing content on the official website, garnering over 1,000 views and sharing insights that helped students in their placement preparation.

Coordinated and efficiently communicated with team members with college seniors, faculty members, to gather valuable insights and feedback for technical content, ensuring accuracy and relevance.

Focused on delivering beginner-friendly content that simplified complex coding concepts, contributing to the placement success of 30+ students who practised the codes for interviews.

Produced original, research-driven technical content on Python and SQL, optimized for clarity and comprehension, conducted extensive research and analysis on Python vs SQL which contributed to a significant increase in placement-related traffic on the official website.


Proofread and edited all content for grammatical accuracy, readability, resulting in a 90% error-free publication rate and created visual aids and infographics to simplify technical concepts, leading to a 20% increase in user engagement.


Select all records from the registration table
SELECT * FROM db_name.tb_name;
Retrieves all columns and rows from the registration table in the db_name.

Select records where Gender is 'Male'
SELECT * FROM db_name.tb_name WHERE Gender = "Male";
Filters the registration table to show records where the gender is "Male".

Select records where city starts with 'A'
SELECT * FROM db_name.tb_name WHERE city LIKE "A%";
Retrieves records where the city column starts with the letter 'A'.

Select records with null values in the phone column
SELECT * FROM db_name.tb_name WHERE phone IS NULL;
Retrieves records from the registration table where the phone field is empty or not specified.

Select records with null values in the whatsapp column
SELECT * FROM db_name.tb_name WHERE whatsapp IS NULL;
Retrieves records from the registration table where the whatsapp field is empty or not provided.

Select all records from the score table
SELECT * FROM db_name.tb_name;
Retrieves all columns and rows from the score table in the db_name.

Select records where class is 10
SELECT * FROM db_name.tb_name WHERE class = 10;
Filters the score table to show records where the class is 10.

Select records where the month of the year is June (Month = 6)
SELECT * FROM db_name.tb_name WHERE MONTH(year) = 6;
Retrieves records where the year column falls in the month of June.

Select records where payment mode is 'cash'
SELECT * FROM db_name.tb_name WHERE payment_mode = "cash";
Filters the score table to show records where the payment_mode is "cash".

Select records with null values in the fee column
SELECT * FROM db_name.tb_name WHERE fee IS NULL;
Retrieves records from the score table where the fee field is empty or not specified.

Select the sum of marks1, marks2, marks3, and marks4 for a specific person
SELECT SUM(marks1), SUM(marks2), SUM(marks3), SUM(marks4) FROM db_name.tb_name WHERE month = "Aritra Biswas";
Calculates the sum of marks for marks1, marks2, marks3, and marks4 for the person named "Aritra Biswas".

Select distinct names from the score table
SELECT DISTINCT name FROM db_name.tb_name;
Retrieves unique names from the score table.

Count the number of distinct classes in the score table
SELECT COUNT(DISTINCT class) FROM db_name.tb_name;
Counts the number of unique classes in the score table.

Select the difference in years between the current date and the 'year' column
SELECT DATEDIFF(CURDATE(), year) AS diff FROM db_name.tb_name WHERE month = "Aritra Biswas";
Calculates the difference in days between the current date and the year column for the person named "Aritra Biswas".

Insights from Quantity Data (Total Quantity: 4899)
Top Performing Categories by Quantity:

External Hard Drive (11.44% of total quantity) and Camera (11.39% of total quantity) are the highest-selling product categories in terms of quantity, indicating strong consumer demand for these items.
These two products could be key drivers of your inventory or revenue generation, and promoting them more could boost sales further.
Least Performing Category by Quantity:

Headphones represent only 7.19% of total quantity, which is the lowest among the products. This suggests there may be less demand for headphones compared to other products, possibly due to market saturation, pricing, or consumer preferences.
Investigating customer feedback or adjusting marketing strategies for headphones could help improve their performance.
Balanced Demand Across Categories:

Many products like Laptop (10.75%), Smartphone (9.53%), Smartwatch (10.11%), and Tablet (9.62%) fall in the range of 9-11% of the total quantity. This shows a fairly even distribution of demand across different categories, indicating that customers are purchasing a diverse range of products from the store or platform.
It could be beneficial to maintain a diverse inventory to meet varying customer needs.

Insights from Sales Data (Total Sales: 51,202,117)
Highest Revenue Generators:
External Hard Drive (11.25% of total sales) and Desktop PC (10.18% of total sales) contribute the most to overall sales, both in terms of quantity and revenue. These two products seem to have high sales prices or premium features, making them strong performers in generating revenue.
Smartphone (10.44%) and Printer (10.83%) also contribute significantly to the revenue, indicating that products with higher sales values are performing well, which is typical in consumer electronics.

Revenue Discrepancy with Quantity:
Despite Camera having a strong sales volume of 11.39% of total quantity, it only generates 10.04% of total sales. This may indicate that the Camera is priced lower compared to other high-volume products like External Hard Drives or Desktop PCs, which are driving higher revenue.
Headphones show a low percentage of total sales (7.83%), which reflects the low demand for this category in terms of revenue as well. The lower price point may contribute to its smaller share of total sales.

Opportunity for Upselling:
Laptop and Smartwatch are performing relatively well in both quantity (10.75% and 10.11%) and sales (9.34% and 10.14%), but there may be an opportunity to increase their average selling price (ASP) or enhance their perceived value through bundles, promotions, or exclusive features.
Smartphone sales, with a 10.44% share, suggest it's a popular category, but marketing strategies around upselling or adding accessories (like headphones or smartwatches) could further boost overall sales.
Price Sensitivity:

Products like Tablet (9.91% in sales) and Smartphone (10.44%) might have a more competitive price range, and could be in direct competition with many other brands. This could indicate a price-sensitive market, and a value proposition based on price vs. features could be key to maximizing sales.
Key Observations and Business Recommendations
Focus on High-Volume, High-Revenue Products:

Focus marketing efforts and inventory planning on products like External Hard Drives, Desktop PCs, and Printers, which are generating the highest revenue. These are likely the most profitable and demand-driven categories, so enhancing their visibility or adding complementary products could increase overall sales.
Address Underperforming Categories:

Headphones, with both low quantity and sales percentages, may require a revised marketing strategy or pricing adjustment. Additionally, checking for any external factors like competition or market demand could help improve sales.
If headphones are part of a bundled package (e.g., with smartphones or laptops), it could help increase their perceived value.
Optimize Inventory Distribution:

Since External Hard Drives and Cameras are top-selling products in quantity, ensuring their availability and prominence in your inventory can help prevent stockouts and improve overall sales. Conversely, underperforming products may need fewer resources allocated for inventory management.
Strategize for Value-Based Selling:

Products that generate high revenue but have slightly lower quantities (like Laptop and Smartphone) might benefit from premium pricing, additional features, or customer-centric marketing strategies. Cross-selling with accessories or offering extended warranties can also increase sales in these segments.
Promote Diversity in Product Categories:

Given that categories like Smartwatch, Tablet, and Smartphone have balanced distribution across both quantity and revenue, emphasizing the variety of products and targeting different consumer segments can help maintain sales consistency across diverse customer groups.

1.	Summarize the above insight and produce 2 bullet points from them for the CV.
Analyzed product performance across 4,899 units sold, identifying top categories (External Hard Drives 11.44% and Cameras 11.39% of total quantity) and high-revenue generators (External Hard Drives 11.25% and Desktop PCs 10.18% of total sales), recommending targeted marketing and inventory strategies to boost profitability.

Identified revenue discrepancies (Cameras: 10.04% of total sales vs. 11.39% of total quantity) and proposed pricing optimization for underperforming products like Headphones (7.19% of total quantity, 7.83% of total sales), as well as strategies to enhance product visibility and bundle offerings for increased sales.


Data Loading and Preprocessing:
First, I imported the dataset from an external source, which was in CSV format. The dataset contained various columns, including sales data, product information, and customer demographics.
I loaded this dataset into Excel for initial exploration. This allowed me to get an overview of the dataset, assess its structure, and identify any data issues such as null values, duplicate records, or inconsistent formatting.
After inspecting the data, I cleaned the dataset by removing null and duplicate values. This step ensured that I was working with accurate and consistent data for further analysis. Additionally, I applied basic formatting (such as date formatting, numerical rounding, etc.) to ensure the dataset was ready for analysis.

Data Transformation and KPI Formation:
Once the data was cleaned, I used Excel’s Pivot Tables to summarize the key performance indicators (KPIs), such as total sales and total quantity sold. Pivot tables helped me aggregate data across various dimensions like product categories, regions, and salespersons.
To further refine the analysis, I utilized VLOOKUP functions to enrich the dataset and add new calculated columns for more granular insights, such as total sales by product or total quantity sold by state.

Data Visualization in Power BI:
For the dashboarding and dynamic reporting part of the project, I used Power BI because it offers powerful capabilities for interactive data visualization and dynamic reporting. Power BI allows for real-time data updates, making it an excellent tool for business intelligence.
I imported the cleaned dataset from Excel into Power BI and started building the dashboard.
To calculate key metrics like total sales and total quantity sold, I created explicit DAX (Data Analysis Expressions) measures. This allowed me to define custom calculations directly in Power BI, ensuring the data was calculated dynamically based on user input and visual context.
I also created a new calculated column using Power BI's Format Formula to extract the month from a given date field. This was important for time-based analysis, allowing us to track trends and patterns over different months.

Interactive Dashboard Design:
The next step was to design an interactive and intuitive dashboard. To make the dashboard more user-friendly and interactive, I utilized slicers to allow users to filter the data by specific attributes like state, product category, and time period.
For the KPI display, I used text cards to highlight important metrics such as total sales, total quantity sold, and other critical KPIs.
I incorporated various visualizations like:
Column charts to show sales performance by product category.
Donut charts for a quick view of market share by region.
Clustered bar charts to compare sales performance across different states.
Matrix tables for detailed breakdowns of sales data by product, state, and month.
Each visualization was formatted carefully, ensuring the data was presented in a clear and concise manner. I also added filters to the charts so users could drill down into specific aspects of the data (e.g., viewing only sales data for a particular region or time period).

Final Presentation and Insights:
The final step was to ensure that the dashboard provided valuable business insights that were easy to understand and actionable. By using Power BI’s interactive capabilities, users could slice and dice the data, drill down into specific trends, and make data-driven decisions.
Some key insights derived from the dashboard included:
Identifying which products had the highest sales performance in specific regions.
Analyzing the monthly sales trends, helping the business anticipate peak seasons and plan inventory accordingly.
Highlighting any regions with underperforming sales, allowing the marketing team to tailor their campaigns or investigate any external factors affecting performance.

Key Skills and Tools Used:
Data Cleaning & Preprocessing: Excel, Removing duplicates, Handling null values
Data Analysis: Pivot Tables, VLOOKUP, DAX Measures in Power BI
Data Visualization: Power BI (Column Charts, Donut Charts, Cluster Bar Charts, Matrix)
Dashboarding: Interactive KPIs, Slicers, Filtering, Time-based Analysis using DAX
Reporting & Insights: Clear and concise data storytelling, Actionable insights for business decisions.

1.	Summarize the above insight and produce 3 bullet points from them for the CV.

Data Cleaning & Preprocessing: Cleaned and prepared a sales dataset with 1,000 rows by removing null and duplicate values, ensuring data consistency for further analysis. Applied Excel functions such as LOOKUP, TEXT and formatting adjustments for accurate reporting and analysis.

Data Analysis & KPI Formation: Created dynamic KPIs using Excel Pivot Tables and Power BI DAX measures to aggregate key metrics (e.g., total sales, total quantity sold) across product categories, regions, and time periods, providing insights for business decision-making.

Interactive Dashboard Design & Reporting: Developed a Power BI dashboard with interactive features (slicers, filters) for real-time data analysis. Included visualizations like column charts and matrix tables to highlight key sales trends, regional performance, and monthly patterns, enabling actionable insights and data-driven decisions.


1. Student Data Management & Organization: Efficiently maintained accurate records for 50 students across classes 6-10, ensuring that academic information was consistently updated in Excel, reducing data discrepancies by 10% over the time period.

Data Collection & Test Score Analysis: Collected and analyzed monthly test scores. Generated monthly reports using Excel, tracking improvements, and providing actionable insights that led to a 15% average improvement in student by developing a competitive mindset.

Customer Service & Communication: Responded to 15+ parent and student whatsapp inquiries each month, providing detailed feedback and recommendations based on student performance, contributing to a 20% increase in student retention.

Content Creation & Proofreading: Prepared study materials, including notes and exam sheets, ensuring all content was accurate, clear, and error-free. Proofreading and revisions helped reduce content errors by 25%, ensuring high-quality learning materials.

Data Reporting & Presentations: Designed and delivered 3-5 PowerPoint presentations each month to the business owner, summarizing student performance, test score trends, which helped to improve tuition services.


Removed the duplicate values and irrelevant data for reporting, analyzed monthly score sheets and bring out the best performing 10% students and least performing 10% students on the basis of total marks, average marks and attendance. prepared a detailed half yearly performance report forr the above 20% students using different charts, adv excel, pivot tables, slicer and conducted them to the parents and owners and the major findings are like attendance is directly proportional to marks as students with 10 and more classes a month have a tendency to increse their average marks by 50%, and 70% parents like to pay in the cash mode, 30% used online payments.
Based on the story above mention 3 bullet points, add some quantitave values. You can add something from your own.

•  Student Data Management & Performance Analysis: Managed and maintained accurate records for 50 students across classes 6-10, reducing data discrepancies by 10%. Analyzed monthly test scores using Excel (Pivot Tables, VLOOKUP) to identify top 10% and bottom 10% performers, leading to targeted interventions and a 15% average improvement in student performance.
•  Data Reporting & Stakeholder Communication: Designed and delivered 3-5 monthly PowerPoint presentations to business owners and parents, summarizing student performance trends. Conducted detailed half-yearly reports using advanced Excel tools (pivot tables, slicers), revealing key insights such as a 50% improvement in average marks for students with 10+ classes per month.
•  Customer Service & Retention: Responded to 15+ parent and student inquiries per month on WhatsApp, providing tailored feedback on student performance. Contributed to a 20% increase in student retention, with insights on payment preferences (70% cash, 30% online) helping to refine business offerings.



Developed a Comprehensive Tkinter Application:
I created a 1000-line Tkinter-based desktop application for managing student data and tuition records. The app featured multiple windows for registration and    academic performance tracking, integrating with a MySQL database for storing and querying data.

Showcased Skills in Data Management & UI Design:
The project demonstrated my proficiency in database management, UI design, and data visualization by implementing features like forms for student registration, marks entry, and performance reports. I used Python and MySQL to ensure seamless data flow between the frontend and backend.

Application Led to Freelance Opportunity:
The success of this personal project caught the attention of School Topper Tuitions, who were impressed by my technical skills in data management and automation. They hired me as a freelance student mediator to manage academic data and student progress.

Contributed to Business Operations:
As a freelancer, I used the application to analyze student performance, create reports, and communicate directly with parents and students. The reports I generated using Excel helped the business owner make informed decisions about tuition strategies.

Showcased Skills in Data Management & UI Design:
The application featured 2 different forms for data input (e.g., student registration, marks entry), and monthly report generation for over 50 students. It allowed for the efficient tracking of 50+ individual scores and generated monthly performance reports, contributing to 20% faster decision-making in student assessments.


Summarize the above in 2 points specially mention "Application Led to Freelance Opportunity" this point.

•  Developed Tkinter Application for Student Data Management: Created a 1,000-line Tkinter-based desktop application that integrated with a MySQL database for managing student registrations, academic performance, and report generation. The app tracked 50+ students, streamlining data entry and performance analysis, and led to a 20% improvement in decision-making speed for student assessments.
•  Application Led to Freelance Opportunity: The success of the project caught the attention of School Topper Tuitions, leading to a freelance role as a student mediator. Utilized the application to generate performance reports, communicate with parents, and assist in shaping tuition strategies based on data-driven insights.


Technical Content Writer & Team Lead
Volunteer || PANDULIPI, Magazine Club of Jalpaiguri Government Engineering College || January 2022 - May 2023

	Led a team of 6 Pythonistas (junior team members) to create highly-engaging, beginner-friendly content for technical audiences, including the most-viewed article: "Code for the Champions". 
	Code for the Champions became the top-performing content on the official website, garnering over 1,000 views and sharing insights that helped students in their placement preparation. 
	Coordinated and efficiently communicated with team members, college seniors, faculty members, to gather valuable insights and feedback for technical content, ensuring accuracy and relevance. 
	Focused on delivering beginner-friendly content that simplified coding concepts, contributing to the placement success of 30+ students who practised the codes for interviews. 
	Proofread and edited all content for grammatical accuracy, readability, resulting in a 90% error-free publication rate and created visual aids and infographics to simplify technical concepts, leading to a 20% increase in user engagement.

correct the above in such a way it must have a good ATS score.

E-Commerce Electronics Data Analysis:
	Cleaned and prepared a sales dataset with 1,000 rows by removing null and duplicate values applied Excel functions such as LOOKUP, TEXT and formatting adjustments for accurate reporting and analysis.
	Created KPIs using Excel Pivot Tables and Power BI DAX measures to aggregate key metrics (e.g., total sales, total quantity sold) across product categories, regions, and time periods, providing insights for business decision-making. 
	Developed a Power BI dashboard with interactive features (slicers, filters) for real-time data analysis. Included visualizations like column charts and matrix tables to highlight key sales trends, state-wise performance, and monthly patterns, enabling actionable insights and data-driven decisions.
	Analysed product performance across 4,899 units sold, identifying top categories (External Hard Drives 11.44% and Cameras 11.39% of total quantity) and high-revenue generators (External Hard Drives 11.25% and Desktop PCs 10.18% of total sales), recommending targeted marketing and inventory strategies to boost profitability. 
	Identified revenue discrepancies (Cameras: 10.04% of total sales vs. 11.39% of total quantity) and proposed pricing optimization for underperforming products like Headphones (7.19% of total quantity, 7.83% of total sales), as well as strategies to enhance product visibility and bundle offerings for increased sales. 

correct the above in such a way it must have a good ATS score.

Freelance Student Mediator
School Topper Tuitions || Flexible || May 2024 - Oct 2024

	Managed and maintained accurate records for 50 students across classes 6-10, reducing data discrepancies by 10%. Analysed monthly test scores using Excel (Pivot Tables, VLOOKUP) to identify top 10% and bottom 10% performers, leading to targeted interventions and a 15% average improvement in student performance.
	Designed and delivered 3-5 monthly PowerPoint presentations to business owners and parents, summarizing student performance trends. Conducted detailed half-yearly reports using advanced Excel tools (pivot tables, charts), revealing key insights such as a 30% improvement in average marks for students with 10+ classes per month. 
	Customer Service & Retention: Responded to 15+ parent and student inquiries per month on WhatsApp, providing tailored feedback on student performance. Contributed to a 10% increase in student retention, with insights on payment preferences (70% cash, 30% online) 
	Developed Tkinter Application for Student Data Management: Created a 1,000-line Tkinter-based desktop application that integrated with a MySQL database for managing student registrationsand academic performance. 
	The success of the project caught the attention of School Topper Tuitions, leading to a freelance role as a student mediator. Utilized the application to generate performance reports, communicate with parents, and assist in shaping tuition strategies based on data-driven insights.

correct the above in such a way it must have a good ATS score.

Technical Skills
•	Programming & Development: Python (Tkinter, Data Analysis, Application Development), SQL (Data Analysis, Reporting), DAX (Power BI)
•	Data Analysis & Reporting: Data Cleaning & Preprocessing (Excel, Pivot Tables, VLOOKUP, Power BI), KPI Formation & Data Aggregation (Excel, Power BI DAX), Performance Analysis & Reporting (Excel, Power BI)
•	Application Development: Tkinter-based Desktop Application (1,000+ lines of code), Database Management (MySQL Integration for Data Storage and Querying)
•	Data Visualization & Dashboarding: Power BI (Dashboard Creation, Interactive Reporting, Visualizations), Excel (Pivot Tables, Slicers, Conditional Formatting)

Non-Technical Skills
•	Team Leadership & Coordination: Led a team of 6 junior team members to create engaging, beginner-friendly technical content. Fostered collaboration to ensure high-quality output and consistency in content development.
•	Communication & Stakeholder Engagement: Coordinated with college seniors, faculty members, and students to gather insights for content, ensuring accuracy and relevance. Maintained strong communication to ensure alignment with stakeholders' needs.
•	Customer Service & Client Retention: Responded to 15+ parent and student inquiries per month via WhatsApp, offering tailored feedback on performance. Contributed to a 20% increase in student retention by building relationships and offering personalized insights.
•	Content Creation & Proofreading: Developed original technical content on Python, SQL, and coding practices. Proofread and edited materials for grammatical accuracy, achieving a 90% error-free publication rate. Created visual aids and infographics to simplify complex concepts, increasing user engagement by 20%.

