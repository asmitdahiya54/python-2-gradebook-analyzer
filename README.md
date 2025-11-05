# python-2-gradebook-analyzer
“A Python program to analyze student grades, calculate statistics, assign grades, and export results to CSV.”
OUTPUT -        GradeBook Analyzer
===================================

Choose an option:
1. Manual data entry
2. Load data from CSV file
3. Exit
Enter your choice (1/2/3): 1
Enter number of students: 6
Enter name of student 1: ASMIT
Enter marks for ASMIT: 77
Enter name of student 2: ADITYA DANGI
Enter marks for ADITYA DANGI: 56
Enter name of student 3: DIKSHIT
Enter marks for DIKSHIT: 56
Enter name of student 4: ANUJ RAGHAV
Enter marks for ANUJ RAGHAV: 34
Enter name of student 5: GURPREET SINGH
Enter marks for GURPREET SINGH: 67
Enter name of student 6: MANISH CHAUHAN
Enter marks for MANISH CHAUHAN: 43

--- Statistical Analysis ---
Average Marks: 55.50
Median Marks : 56.00
Highest Score: 77.0
Lowest Score : 34.0

Grade Distribution:
-------------------
Grade C: 1 student(s)
Grade F: 4 student(s)
Grade D: 1 student(s)

Pass / Fail Summary:
--------------------
Passed (5): ASMIT, ADITYA DANGI, DIKSHIT, GURPREET SINGH, MANISH CHAUHAN
Failed (1): ANUJ RAGHAV

Final Results Table
---------------------------
Name            Marks   Grade
---------------------------
ASMIT           77.0    C
ADITYA DANGI    56.0    F
DIKSHIT         56.0    F
ANUJ RAGHAV     34.0    F
GURPREET SINGH  67.0    D
MANISH CHAUHAN  43.0    F
---------------------------

Do you want to save results to CSV file? (y/n): Y

Results exported successfully to 'final_results.csv'

Do you want to analyze another dataset? (y/n): N
Thank you for using GradeBook Analyzer!
