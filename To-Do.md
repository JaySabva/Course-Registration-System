# 1. Login (/login)
   ### Input
     - Username
     - Password
    
  ### Return
    - jwt
    - username

# 2. Admin (/admin)
  ## Add Professor (/add-professor)
    -> Input
      - name, email, password
  ##  Add Semester (/add-semester)
    -> Input
      - semesterName, startDate, endDate
  ## Add Course (/add-course)
    -> Input
      - courseName, capacity, remainingSeats, professorId, semesterId, courseCredit

  ## Add Student (/add-student)
    -> Input
      - name, email, password
    Bonus: send email with credentials, also send the email for the deadline

# 3. Student (/student)
  ## Get Course List (/get-course-list)
    -> return
      - CourseName, courseID, courseProf, courseGrade

  ## submit-course-form (/submit-course-form)
    -> Input
      - requestedCourseIDs(array), requestedDate, studentId (jwt can work insted of this redandant)

  ## update student (/update-student/{id})
    -> just use jwt nothing else


      
