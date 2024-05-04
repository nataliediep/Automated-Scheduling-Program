# Natalie's Automated Scheduling Application

This is an interactive automated scheduling program that generates employee work schedules using Python for backend, and React.js and Flask for frontend. The program will ultimately produce two different Excel files: a **weekly** work schedule and **daily** work schedule.

While there are plenty of existing scheduling tools, they come with upfront costs to use. This program is entirely free! (I also wanted to take on the challenge of creating my own Python-driven web application, coming from a non-CS background and limited programming skills.)

The objective of this program is to generate an **Excel file containing a master weekly work schedule**. Based on business demands and special events/holidays, the program will determine the appropriate number of employees needed at a specific hour to ensure smooth business operations. This program will equitably schedule employees based on their availability, performance, and requested days off.

This program was built to be used by the USC Bookstore's scheduling team. With this program, the scheduling team no longer needs to spend ridiculous hours manually creating a single weekly schedule by hand – the process is now entirely automated. Fight on!


## A quick overview of this program's main features
1. Generates an Excel file containing a weekly work schedule for all employees.
2. Indicate specific dates/times when more employees will be needed.
3. An adjustable "bias" feature that will more or less take into consideration an employee's performance rating. Can be turned on or off.
4. **An interactive, easy to use UI that allows manual user inputs.**


## How to use this program

To start, you will need to provide a master availability sheet containing the availabilities of all employees. This master availability sheet will also store the employee's performance rating and their requested days off.

**In order for the program to work, the master availability sheet must utilize the exact same format as shown in the example sheet named "EXAMPLE_MASTER_AVAILABILITY.xlsx".** A blank master availability sheet is provided, so you can fill and update it as needed.


