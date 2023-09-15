# 14.10 LAB: Course Grade

Write a program that reads the student information from a tab separated values (tsv) file. The program then creates a text file that records the course grades of the students. Each row of the tsv file contains the Last Name, First Name, Midterm1 score, Midterm2 score, and the Final score of a student. A sample of the student information is provided in StudentInfo.tsv. Assume the number of students is at least 1 and at most 20. Assume also the last names and first names do not contain whitespaces.

The program performs the following tasks:

Read the file name of the tsv file from the user.
Open the tsv file and read the student information.
Compute the average exam score of each student.
Assign a letter grade to each student based on the average exam score in the following scale:
A: 90 =< x
B: 80 =< x < 90
C: 70 =< x < 80
D: 60 =< x < 70
F: x < 60
Compute the average of each exam.
Output the last names, first names, exam scores, and letter grades of the students into a text file named report.txt. Output one student per row and separate the values with a tab character.
Output the average of each exam, with two digits after the decimal point, at the end of report.txt. Hint: Use the format specification to set the precision of the output.

![image](https://github.com/PonguTracer/Course-Grade/assets/67764701/57c4e20a-2a06-4da5-9ad6-1dae5087a7f3)
