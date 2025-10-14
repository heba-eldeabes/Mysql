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
  ![img2](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2014-19-36.png) 

  ![img2](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2014-20-21.png)

  ![img3](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2014-20-37.png)
 
 ![img4](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2014-55-25.png)

 ![img5](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2014-55-43.png)

![img6](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2015-07-59.png)

![img7](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2015-10-11.png)
![img8](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2015-11-13.png)
![img9](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2015-11-44.png)

![img11](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2016-21-14.png)
![img12](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-13%2016-22-41.png)

![img14](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-14%2010-55-13.png)
![img15](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-14%2011-02-08.png)
![img16](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-14%2011-11-37.png)
![img17](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-14%2011-21-00.png)
![img18](https://github.com/heba-eldeabes/Mysql/blob/main/img/Screenshot%20from%202025-10-14%2011-27-00.png)