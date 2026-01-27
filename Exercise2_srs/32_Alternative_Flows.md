# Alternative Flows

Alternative flows describe the possible variations or exceptions that may occur during the normal execution of system operations in the Student Result Management System. These flows handle error conditions and unexpected scenarios, ensuring that the system behaves correctly under all circumstances.

During the user login process, if incorrect credentials are entered, the system displays an error message and prompts the user to re-enter valid details. If multiple failed attempts occur, the system may temporarily restrict access for security purposes.

In the result entry process, if a faculty member enters invalid marks or incomplete data, the system requests correction before allowing the data to be saved. This ensures data accuracy and prevents incorrect academic records.

While viewing results, if results are not yet published or data is unavailable, the system displays an appropriate notification to the student instead of showing incorrect information. In the case of system or database issues, a warning message is displayed, and the user is guided to try again later.

Including alternative flows improves system reliability, enhances user experience, and ensures that the Student Result Management System handles errors gracefully.
