# Class Attributes and Methods

The identification of class attributes and methods helps define the structure and behavior of the Student Result Management System.

| **Class Name**    | **Attributes**                         | **Methods**                                          |
| ----------------- | -------------------------------------- | ---------------------------------------------------- |
| **User**          | userId, username, password, role       | login(), logout(), authenticate()                    |
| **Student**       | studentId, name, department, semester  | viewResults(), checkBacklogs(), viewPerformance()    |
| **Faculty**       | facultyId, name, department            | enterMarks(), updateMarks(), verifyResults()         |
| **Administrator** | adminId, name, email                   | addUser(), updateUser(), deleteUser(), manageRoles() |
| **Subject**       | subjectCode, subjectName, credits      | getSubjectDetails()                                  |
| **Result**        | resultId, marks, grade, passFailStatus | calculateGrade(), determineStatus()                  |
