# Mysql 
  ## Install MYSQL DBMS.
  ## 2.Design ERD and write down the mapping schema. 
![img1](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-07%2000-28-01.png)
  ## electronic_gradekeeping database
  ## Entities:
  ---------
 ## 1. Student
   - Student_ID (Primary key)
    - Name
    - Email
  - Address
---------------------------------------------------------------
 ## 2. Phone
- Phone_ID (Primary key)
- Phone_Number
- Student_ID (Foreign key referencing Student)
---------------------------------------------------------------
 ## 3. Subject
- Subject_ID (Primary key)
- Name
- Description
- Max_Score
---------------------------------------------------------------
 ## 4. Student_Subject
- Student_ID (Foreign key referencing Student)
- Subject_ID (Foreign key referencing Subject)
- PRIMARY KEY (Student_ID, Subject_ID)
---------------------------------------------------------------
 ## 5.Exam
- Exam_ID (Primary key)
- Exam_Date
- Subject_ID (Foreign key referencing Subject)
---------------------------------------------------------------
## 6. Exam_Result
- Exam_ID (Foreign key referencing Exam)
- Student_ID (Foreign key referencing Student)
- Score
- PRIMARY KEY (Exam_ID, Student_ID)
---------------------------------------------------------------
 ## 3.Create your mapped tables with their columns.
