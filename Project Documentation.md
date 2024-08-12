## Project 1: Human Resource Analytics Dashboard
## Dashboard Link:  https://app.powerbi.com/groups/me/reports/e2689d99-0dee-4ed5-93fe-8b9291d3f6d8/871196bbaa26f86d6085?redirectedFromSignup=1&experience=power-bi
### Introduction
The Human Resource Analytics Dashboard provides an interactive way to visualize and analyze HR data. It includes insights into job roles, business travel, headcount, salary distribution, performance ratings, and demographic breakdowns by gender and age. This dashboard is designed to assist HR departments in making data-driven decisions.
### Features
1. *Job Role (Vertical Drop-Down Slicer)*
   - Allows users to filter data based on different job roles.
2. *Business Travel (Vertical Drop-Down Slicer)*
   - Enables filtering data based on business travel status.
3. *Headcount (Card)*
   - Displays the total number of employees.
4. *Average Salary by Education Field (Lollipop Chart)*
   - Visualizes average salaries segmented by education fields.
5. *Headcount by Gender (Pie Chart)*
   - Shows the distribution of headcount by gender, including percentage and total values.
6. *Headcount by Age and Gender (Dual Bar Chart)*
   - Presents a breakdown of headcount by both age and gender.
7. *Average Performance Rating (Meter Gauge Chart)*
   - Illustrates the average performance rating across the organization.
8. *Table*
   - Displays a detailed table with columns for Job Role, Average Salary, Headcount, Maximum Salary, and Minimum Salary.
### Technical Details
#### 1. *Job Role (Vertical Drop-Down Slicer)*
   - *Data Source:* HR Database - Job Roles Table
   - *Field Used:* JobRole
   - *Description * Allows users to select specific job roles to filter the dashboard data accordingly.
#### 2. *Business Travel (Vertical Drop-Down Slicer)*
   - *Data Source:* HR Database - Employee Travel Table
   - *Field Used:* BusinessTravel
   - *Description:* Enables filtering of data based on whether employees travel for business.
#### 3. *Headcount (Card)*
   - *Data Source:* HR Database - Employee Count Table
   - *Field Used:* EmployeeCount
   - *Description:* Displays the total number of employees.
#### 4. *Average Salary by Education Field (Lollipop Chart)*
   - *Data Source:* HR Database - Salary and Education Table
   - *Field Used:* AverageSalary, EducationField
   - *Description:* A lollipop chart showing average salary for each education field.
#### 5. *Headcount by Gender (Pie Chart)*
   - *Data Source:* HR Database - Gender Breakdown Table
   - *Field Used:* Headcount, Gender
   - *Description:* A pie chart that shows the headcount distribution by gender with percentage and total count.
#### 6. *Headcount by Age and Gender (Dual Bar Chart)*
   - *Data Source:* HR Database - Age and Gender Table
   - *Field Used:* Headcount, Age, Gender
   - *Description:* A dual bar chart depicting headcount distribution across different age groups and gender.
#### 7. *Average Performance Rating (Meter Gauge Chart)*
   - *Data Source:* HR Database - Performance Ratings Table
   - *Field Used:* AveragePerformanceRating
   - *Description:* A meter gauge chart representing the average performance rating.
#### 8. *Table*
   - *Data Source:* HR Database - Job Role Summary Table
   - *Fields Used:* JobRole, AverageSalary, Headcount, MaximumSalary, MinimumSalary
   - *Description:* A table providing detailed information on job roles, average salaries, headcount, and salary ranges.
### Implementation Steps
1. *Data Connection:*
   - Connect Power BI to the HR Database using appropriate credentials and data sources.
2. *Data Transformation:*
   - Clean and prepare data using Power Query Editor. Ensure correct data types and relationships are established.
3. *Visualizations:*
   - Create each visualization according to the specifications. Apply necessary filters and slicers to enable user interaction.
4. *Design Layout:*
   - Arrange visualizations on the Power BI report canvas for a coherent and user-friendly layout.
5. *Testing:*
   - Verify each visual and slicer functions correctly. Ensure data accuracy and interactive filters are working as expected.
6. *Deployment:*
   - Publish the Power BI report to Power BI Service and configure sharing settings as needed.
### Conclusion
This Power BI dashboard offers a clear overview of key HR metrics, empowering data-driven decisions for effective workforce management.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Project 2: Amazon Prime Video Analysis
## Dashboard Link: https://app.powerbi.com/groups/me/reports/21335e2b-0e3f-40f5-8478-5ab6b457290f/61a8bf63af9e8d4c9fd1?experience=power-bi
## Introduction
The Amazon Prime Video Analytics Dashboard offers a comprehensive view of the streaming platform's content landscape. This dashboard is designed to provide insights into various metrics such as the total number of titles, ratings, genres, and directors, as well as detailed breakdowns by country, show type, and release year. By leveraging this dashboard, users can gain valuable insights into content distribution, audience preferences, and performance trends across different regions and categories.
## Features
1. *Total Titles (Card)*
   - Displays the total number of titles available on Amazon Prime Video.
2. *Total Ratings (Card)*
   - Shows the total number of ratings given across all titles.
3. *Total Genres (Card)*
   - Indicates the total number of distinct genres available on the platform.
4. *Total Directors (Card)*
   - Presents the total number of unique directors involved in the content.
5. *Start Date (Card)*
   - Shows the earliest date of content availability or the start of the dataset.
6. *End Date (Card)*
   - Displays the most recent date of content availability or the end of the dataset.
7. *Ratings by Total Show (Bar Chart)*
   - Illustrates the distribution of ratings across different shows, highlighting the relationship between ratings and the number of shows.
8. *Genres by Total Shows (Bar Chart)*
   - Visualizes the number of shows per genre, showing which genres are most and least prevalent.
9. *Total Shows by Country (Map Visual)*
   - Provides a geographic view of the number of shows available in different countries.
10. *Movie and TV Show (Doughnut Chart)*
    - Shows the total number and percentage of movies versus TV shows on the platform.
11. *Total Shows by Release Year (Movies, TV Shows) (Line Chart)*
    - Displays the trend of shows released by year, segmented into movies and TV shows.
## Technical Details
### 1. Total Titles (Card)
   - *Field Used:* Total Titles
   - *Description:* Displays the count of all titles available on Amazon Prime Video.
### 2. Total Ratings (Card)
   - *Field Used:* Total Ratings
   - *Description:* Shows the aggregate number of ratings across all titles.
### 3. Total Genres (Card)
   -  *Field Used:* Total Genres
   - *Description:* Displays the count of distinct genres.
### 4. Total Directors (Card)
   - *Field Used:* Total Directors
   - *Description:* Shows the count of unique directors.
### 5. Start Date (Card)
   - *Field Used:* StartDate
   - *Description:* Indicates the earliest date available in the dataset.
### 6. End Date (Card)
   - *Field Used:* End Date
   - *Description:* Shows the most recent date available in the dataset.
### 7. Ratings by Total Show (Bar Chart)
   - *Field Used:* Ratings, Show Name
   - *Description:* A bar chart showing the ratings distribution for each show.
### 8. Genres by Total Shows (Bar Chart)
   - *Field Used:* Number of Shows, Genre
   - *Description:* A bar chart displaying the number of shows per genre.
### 9. Total Shows by Country (Map Visual)
   - *Field Used:* Country, Number of Shows
   - *Description:* A map visual showing the number of shows available in different countries.
### 10. Movie and TV Show (Doughnut Chart)
   - *Field Used:* Content Type, Total Count
   - *Description:* A doughnut chart illustrating the proportion of movies versus TV shows.
### 11. Total Shows by Release Year (Movies, TV Shows) (Line Chart)
   - *Field Used:* Release Year, Show Type
   - *Description:* A line chart depicting the number of shows released each year, segmented by type (movies or TV shows).
## Implementation Steps
1. *Data Connection:*
   - Connect Power BI to the data sources, ensuring access to content metadata, ratings, genres, directors, and other relevant tables.
2. *Data Transformation:*
   - Clean and prepare the data using Power Query Editor. Ensure accurate data types and relationships between tables.
3. *Visualizations:*
   - Create each visualization according to the specifications. Configure slicers and filters to enable user interaction.
4. *Design Layout:*
   - Arrange the visualizations on the Power BI report canvas for clarity and ease of use.
5. *Testing:*
   - Verify that all visuals and slicers function correctly. Ensure data accuracy and interactivity.
6. *Deployment:*
   - Publish the Power BI report to Power BI Service and set up sharing and permissions.
## Conclusion
The Amazon Prime Video Analytics Dashboard provides a powerful tool for analyzing and understanding content distribution, audience engagement, and performance metrics. By leveraging this dashboard, stakeholders can make informed decisions regarding content strategy and audience targeting. The visualizations and insights offered in this report facilitate a deeper understanding of the streaming platform’s content landscape, ultimately supporting more strategic and data-driven decisions.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
