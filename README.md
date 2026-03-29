# 🎓 Student Grade Analyzer

 A Python command-line tool that reads student marks from a CSV file, calculates grades, rankings, and subject statistics, then generates a formatted report. 

## 📊 Features
 - Reads and parses CSV data using Python file I/O 
 - Calculates per-student averages, percentages, and letter grades
 - Ranks students by performance 
 - Computes subject-wise class averages 
 - Generates timestamped report.txt in output/ folder
 - Handles missing/invalid data with error handling 
 
 ## 🛠 Tools Used
  - Python 3.x 
  - Built-in modules: os, datetime

 ## 📁 Input Format (students.csv) 
 ``` Name,Math,English,Science,Hindi Arjun,88,74,91,80 Priya,65,82,70,75 ```

 ## 📸 Sample Output 
![Sample Output](Screenshot%202026-03-29%20173726.png)

 ## 🧠 What This Demonstrates 
 - Dictionary and list comprehensions 
 - File I/O (reading + writing) 
 - Error handling with try/except 
 - Lambda + sorted() for rankings
 - String formatting with f-strings