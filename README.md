# Analyzing-Job-Market-Data 📊
## Scope :page_with_curl:
This report is focused on exploring a real-world job posting dataset to uncover insights for a fictional recruitment company.

I used visualization techniques to investigate the data to find out what skills are most in-demand for data scientists, data analysts, and data engineers.

Useful insights were obtained.
## Data Design :bar_chart:
The raw data provided were downloaded in CSV file formats and it came with some of its contents being improperly formatted hence, a proper data cleaning had to be done.
## Import and Transform Data :scroll:
After downloading the data which was in CSV file format, I imported the data into Tableau being the tool I’ll be using for analysis and visualization.

<img width="737" alt="TABLEAU JOB PROJ 1" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/264fe6c1-1edf-4c0e-ab7b-21b1e41b4b8d">

##
Now, you see below, All columns in the dataset are loaded.

Tableau recognized the "Job posting ID" field as a "Measure" instead of a "Dimension", I changed it to be a "Dimension".

<img width="318" alt="TABLEAU JOB PROJ 2" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/c3b94ce8-021f-407d-b905-692261697aef">

## Data Cleaning/Check :shower:
For any analysis, missing values can have a huge impact.
I investigate whether the "Minimum Pay" column has any missing values.

<img width="411" alt="TABLEAU JOB PROJ 3" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/cfed4672-c232-41eb-aa30-3df6625e66ab">

## Exploratory Data Analysis (EDA) 📊
I created a bar chart showing the total number of job applicants per company industry.

Then I checked for how many distinct values there are in "Company Industires".

Finally, I sorted the bar chart by Total Number of Applicants per Industry.

<img width="550" alt="TABLEAU JOB PROJ 4" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/e33ed9a7-4efd-4147-931d-ccbd706c6b39">

##
To have an understanding of the relationship between "Years of Experience' and "Job Position Level", I created a Column chart.
But I changed the Measure from "Sum" to "Average".

<img width="358" alt="TABLEAU JOB PROJ 5" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/8e5adeb2-a68f-4d21-a2c6-96359fb6b7ec">

##
I sorted the "Average Years of Experience" in Ascending Order.

<img width="602" alt="TABLEAU JOB PROJ 6" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/7a33727e-b9d9-450a-bf59-a92957f6a0c1">

##
I used the "Job postings date" column to visualize the distinct number of postings per month, and used "Job Position Level" to differentiate these Job Postings.

<img width="439" alt="TABLEAU JOB PROJ 7" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/9a72a3a0-92b8-49ee-a3c6-a69673c83c74">


## Analysis & Visuallization 📈
I visualized the count of all the different Job titles compared to each other.     

<img width="658" alt="TABLEAU JOB PROJ 8" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/dba5cd2b-e86b-47b5-8a49-306ff672983a">

##
I created a calculated field called "Average Pay" which calculates the average salary using "Minimum Pay" and "Maximum Pay".

<img width="572" alt="TABLEAU JOB PROJ 9" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/068f153c-fa58-48c7-8eb6-27b9aa38dfbb">

##
I visualized the average pay per years of experience. 

<img width="655" alt="TABLEAU JOB PROJ 12" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/fc7d348f-70a9-4ef5-aece-1ad938611c89">

##
**KEY INSIGHT**
(1) As years of experience increase for a job, so does the associated salary.

(2) There are many empty values for salary inforamtion from postings.

(3) Job postings over the last 5 years are tranding upwards.

## The Dashboard

<img width="868" alt="Job Market Analysis DASHBOARD" src="https://github.com/Marvykeys/Analyzing-Job-Market-Data/assets/130637591/19ef36fe-57a1-4f68-b059-499e192ae8b4">

## THE FINAL INTERACTIVE DASHBOARD :art:
[Dashboard](https://public.tableau.com/views/JobPostingProject/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
