# Use Case Relationships

Use case relationships describe how different use cases in the Student Result Management System are connected to each other. These relationships help in organizing system functionality and avoiding duplication of common actions. The main types of use case relationships used in this project are Include, Extend, and Generalization.

The Include relationship is used when a common functionality is required by multiple use cases. For example, the Login use case is included in other use cases such as View Results, Enter Marks, and Manage Users, as users must authenticate before performing these actions.

The Extend relationship is used when a use case adds optional or conditional behavior to another use case. For instance, Backlog Identification extends the View Results use case, as backlog details are displayed only if a student has failed in one or more subjects.

The Generalization relationship is used to represent shared behavior among similar actors or use cases. In this system, actors such as Student, Faculty, and Administrator share the common Login use case but perform different actions after authentication based on their roles.

Defining use case relationships improves system clarity, enhances modularity, and helps in creating accurate and meaningful use case diagrams for the Student Result Management System.
