# Pewlett-Hackard-Analysis

Overview of the analysis:

Using CSVs with data from our company which contained data such as employee numbers, department numbers, salaries, birth dates, and hire dates, we have built a database which raises some red flags. In the following sections, I will outline the challenge we face in a short time utilizing database connections, and direct our attention to a solution. This image is our ERD for the database connections within the provided CSV files. 
<br>
![Dept_Breakdown](https://user-images.githubusercontent.com/85216568/145456268-0eb4ffb0-8926-4d2a-96ba-cccde5300b07.png)
<br>
Results:

- First, the bad news! The bad news is that we have 90,398 employees ready to retire! 
<br> ![Retiring Titles](https://user-images.githubusercontent.com/85216568/145457031-638360e3-98e5-4880-90a4-cb596a5e131d.png)
<br>
- Secondly, we can find this data by utilizing the 'retiring_titles.csv' file, in which we can view employees by their highest title achieved as well as their retirement elegibility.   
- Thirdly, out of these 90,398 employees, 57668 of them are senior staff in our organization and therein we see the problem. Our most knowledgable employees are headed out of the door.
- Finally, we have a solution! Mentorship; The perfect way to pass on this valuable expierence gathered over years in our organization, imparted to our younger, up and coming employees.

Summary:

These numbers do not look good, and any way you slice it, we here at Pewlett-Hackard have a daunting task ahead of us. We must use this valuable resource of acquired knowledge while we have access to it. I propose a mentorship program that will transition these most senior staff into a part-time trainer role where they have shorter hours, less workload, and an immeasurable ability to be more of an asset to our company. According to the data garnered from the 'mentorship_eligibility.csv' file, We see that we have access to 1,549 employees that are in the target range for desired mentors. 
<br>
![mentorship_eligibility snip](https://user-images.githubusercontent.com/85216568/145457149-5bde2ae1-c5f5-425e-a4c2-3a06029cd075.png)
<br>

  We will have to fill over 57,000 senior roles within our company, and we only have 1549 candidates to accomplish this feat. In this scenario, a one to one mentorship would be ineffective. I propose a conference series filled with speakers in critical areas within our company, available by both in person and virtual access, in which the target mentors can convey their knowledge and passion for our company in such a way as to make the most positive and profitable impact on our company and culture.

Questions from the data: 

- As seen in the database build, we have multiple entries for employees in the 'titles' table, with all titles listed grouped by employee and transition date.
- As seen in the 'manager_info' table, we only have 5 of our 9 department's Managers listed in our data. Who are these missing Managers so that we can pass on this proposal to all involved?
- I need Manager names for the Marketing, Finance, Development, and Quality Management Departments. 
<br> ![manager_info](https://user-images.githubusercontent.com/85216568/145457248-7656b2a7-47b9-4666-b47d-e3a5ae749c65.png)
<br>
