Write a program that:
1. Take the file as an input.
2. Programmatically analyze the file and print in console the name and position of employees .
      a) who has worked for 7 consecutive days.
      b) who have less than 10 hours of time between shifts but greater than 1 hour.
      c) Who has worked for more than 14 hours in a single shift.

a) Employees who have worked for 7 consecutive days:
Theory:
For this analysis, we need to identify employees who have worked continuously for 7 days. This involves checking the 'Time In' entries for each employee and determining if there is a sequence of 7 consecutive days.

Implementation:
The code sorts the data by 'Time In' and then iterates through the entries for each employee, checking if there is a sequence of 7 consecutive days. If such a sequence is found, it prints the name and position of the employee.

b) Employees who have less than 10 hours of time between shifts but greater than 1 hour:
Theory:
This analysis aims to identify employees who have a short break between two consecutive shifts. It involves comparing the 'Time Out' of one shift with the 'Time In' of the next shift, calculating the time difference, and checking if it is less than 10 hours but greater than 1 hour.

Implementation:
The code iterates through the entries, calculates the time between shifts, and prints the names and positions of employees who meet the criteria.


c) Employees who have worked for more than 14 hours in a single shift:
Theory:
This analysis focuses on identifying employees who have worked exceptionally long hours in a single shift. It involves calculating the duration of each shift by subtracting 'Time In' from 'Time Out' and checking if it exceeds 14 hours.

Implementation:
The code iterates through the entries, calculates the duration of each shift, and prints the names and positions of employees who have worked for more than 14 hours in a single shift.


   
