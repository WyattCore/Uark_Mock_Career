# Uark_Mock_Career
<img width="1323" height="764" alt="image" src="https://github.com/user-attachments/assets/c34edc1a-33d5-4b5c-bdba-2caff48f94ef" />



This is a brief database project I came up with to simulate data management for a mock University of Arkansas Career Fair.

I utilizied MySQL Workbench and PowerBi. I used the following techniques:

CREATE DATABASE, CREATE TABLE, INSERT INTO/VALUES, SELECT/AS/FROM, LEFT JOIN, WHERE, GROUP BY, ORDER BY

For column specification I used:

INT PRIMARY KEY AUTO_INCREMENT, VARCHAR(x) NOT NULL, ENUM, INT, DECIMAL, UNIQUE, CONSTRAINT/FOREIGN KEY/REFERENCES, DEFAULT

 ## I used LEFT JOIN to combine tables and demonstrate the following: 

 Offers by major, average summer offer, number of applications/interview/offers from each employer, and the students with the most offers and highest GPAs.



# I created the following tables with the following columns:

## Students: 

student_id, first_name, last_name, class_year, major_id, gpa, grad_term, email 

## Applications: 

app_id, student_id, employer_id, role_title, app_date, source, status, salary_offer, term

## Employers:

employer_id, name, industry, city, state

## Majors

major_id, major_name
   
    
   
   

   
    
   
    
    
