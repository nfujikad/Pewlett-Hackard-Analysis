# Pewlett-Hackard-Analysis

## Analysis Overview
For this analysis, two tables were created to quantify the number of retiring employees and their positions, and one to identify employees who are eligible for the mentorship program. The first table includes enployee information, such as employee number, first and last name, position title, and start and end date. The second table has employee number, first and last name, birth date, start and end date, and position title. 

## Resources
-   Software: pgAdmin4

## Results
The table with returing employees is:
 [retiring_titles.csv](https://github.com/nfujikad/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)

The table with mentorship candidiates is:
[mentorship_eligibility.csv](https://github.com/nfujikad/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

Key Points
1.) The majority of the retireees are in senior poritions, accounting for 2/3 of retirees. One-third are senior engineers and another third are senior staff
2.) The company should prioritize positions that either fill the Senior Engineer and Senior Staff roles or positions that can fill these roles in the future after mentoring.
3.) Among the retireees, 1,549 qualify for the mentorship program.
4.) There are more people retiring than there are potential mentors, which means that the company would have to create an efficient program that can cover the disparity between the number of people retiring and the number of people who can be trained to fill these positions.

## Summary
1.  In order to efficiently train and transition junior staff into higher positions, it is important to determine how many roles will need to be filled as employees retire. A graph can be used to categorize the retirees into age groups. If it is assumed retirement is 65, then hiring can be conducted accordingly. Using a list of people born between 1952 and 1955, a hiring quota for each of the following four years can be generated.

2.  Currently there are not enough retirees to mentor the next generation of employees. In the future a query can be generated that provides a list of employees retiring at the end of the current year (and for each following year). Using this method, the company can prioritize how many younger employees need to be mentored to fill higher positions. Additionally, it would be of benefit to create a query that groups mentor-eligible employees into position titles, this way the program can specifically identify how many mentees a mentor can take on to fulfill the retired roles. 