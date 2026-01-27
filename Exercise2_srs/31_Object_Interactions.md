# Object Interactions

Object interactions describe the way different objects within the Student Result Management System communicate and work together to complete system operations. These interactions define how data flows between objects and how responsibilities are shared among system components during execution.

When a user attempts to log in, the User object sends authentication details to the Authentication Module. The authentication module interacts with the Database object to validate the user credentials. If the credentials are correct, a success response is returned, and the user gains access to the system dashboard.

During the result entry process, the Faculty object interacts with the Result object to enter or update student marks. The Result object processes the data and communicates with the Database object to store the information securely. Validation checks are performed to ensure data accuracy before saving.

For result viewing, the Student object sends a request to the system interface. The system interacts with the Result object, which retrieves the required academic data from the Database object. The results, including grades and backlog details, are then displayed to the student.

These object interactions ensure proper coordination among system components, maintain data integrity, and support efficient execution of system functionalities. Clearly defining object interactions helps in understanding system behavior and serves as a foundation for sequence and activity diagram design.
