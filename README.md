# -APCS-Amusement-Park
An assignment done in my Honors CS Class


Directions

Your goal is to write a program that will calculate the amount of money paid to an employee at the APCS Amusement Park based on their work data. First, some context…

Most hourly workers have to “clock in” and “clock out” when they go to work to calculate how much money they will earn for the hours they work. Many employers hire someone called a “controller”, who will review all of the hourly worker information and enter their work data into a system to calculate their weekly pay. Your task is to write a program that the controller could use to calculate the take home pay for an APCS Amusement Park employee. 

The APCS Amusement Park offers employees different hourly rates for working in different areas of the park (some jobs are easier than others). The park is open every day from 9:00 a.m. to 5:00 p.m. Every employee is required to  work 2 days a week so that everyone has the opportunity to work. 

The Business Office wants us to write our program so that the controller can enter data for each employee and their two days of work in a single line to make this easier for them. The following format will be used for data entry:

location, day, startTime, endTime, location, day, startTime, endTime

Note: Work Day #1 Data and Work Day #2 Data entered in one line

See the codes on the next page that will be used for each piece of data to be entered. 
Program Codes

The following codes will apply to the data entry format

Day Codes

Sunday = 1 | Monday = 2 | Tuesday = 3 | Wednesday = 4

Thursday = 5 | Friday = 6 | Saturday = 7

Start Time / End Time Codes

9:00 = 1 | 9:30 = 2 | 10:00 = 3 | 10:30 = 4 | 11:00 = 5 | 11:30 = 6     	
12:00 = 7 | 12:30 = 8 | 1:00 = 9 | 1:30 = A | 2:00 = B | 2:30 = C | 3:00 = D      3:30 = E | 4:00 = F | 4:30 = G | 5:00 = H

Work Location Codes
 
Locations 100-199 get paid $10.00 per hour for the first 5 hours, and time and a half (150% of base pay) for any hours worked after the first 5 during a shift.

Locations 200-299 get paid $7.50 per hour for the first 6 hours, and double time (200% of base pay) for any hours worked after the first 6 during a shift.

Locations 300-399 get paid $9.25 for the first 4 hours and $10.50 for any hours worked after the first 4 during a shift.

Locations 400-499 get paid $13.50 per hour on Sundays (day 1) and Saturdays (day 7) and $6.75 per hour on other days.

Locations 500-599 get paid $8.00 per hour for the first 6 hours per day, and $12.00 per hour for any hours worked after the first 6 during a shift.


See example runs and test data on the next page…

Example Runs / Test Data

The program should print the total amount of money that the employee should be paid over the 2 days they work per week. Each total pay printout should round the ending value to 2 decimal places, as well as annotate the amount with a dollar sign ($).   

Input:	125, 2, 1, 7, 125, 3, 5, H 
Output:	$95.00

Input: 	214, 4, 1, H, 314, 5, 5, H  
Output:	$133.00

Input:	318, 1, 1, H, 319, 3, 3, D 
Output:	$126.50

Input: 	423, 1, 1, 7, 500, 2, 5, H  
Output:	$88.50

Input:	529, 6, 1, G, 100, 4, 2, G 
Output:	$146.00

