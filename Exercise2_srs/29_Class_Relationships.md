# Class Relationships

Class relationships describe how different classes in the Student Result Management System are connected and interact with each other. These relationships help in understanding system structure and behavior and are essential for designing the class diagram.

The User class acts as a general class that represents common authentication and authorization details. The Student, Faculty, and Administrator classes are specialized forms of the User class. This relationship is represented using generalization, where all three inherit common attributes and methods from the User class.

The Student class is associated with the Result class, as each student can have one or more result records corresponding to different subjects and semesters. The Faculty class is also associated with the Result class because faculty members are responsible for entering, updating, and verifying student marks.

The Result class is linked to the Subject class, as each result corresponds to a particular subject. This association helps in maintaining subject-wise academic performance. The Administrator class is associated with the User class, as the administrator manages user accounts, roles, and access permissions.

These class relationships ensure proper interaction between system components and support accurate system modeling for the Student Result Management System.

# Class Relationships Table

| **Class 1**   | **Relationship Type** | **Class 2**   | **Description**                                                             |
| ------------- | --------------------- | ------------- | --------------------------------------------------------------------------- |
| User          | Generalization        | Student       | Student is a specialized type of User with student-specific attributes.     |
| User          | Generalization        | Faculty       | Faculty is a specialized type of User with faculty-specific functions.      |
| User          | Generalization        | Administrator | Administrator is a specialized type of User with administrative privileges. |
| Student       | Association           | Result        | A student can have one or more result records.                              |
| Faculty       | Association           | Result        | Faculty enters and verifies student results.                                |
| Subject       | Association           | Result        | Each result is associated with a specific subject.                          |
| Administrator | Association           | User          | Administrator manages user accounts and roles.                              |
