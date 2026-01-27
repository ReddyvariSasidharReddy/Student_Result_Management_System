# Use Case Documentation

# Use Case 1: User Login

| **Field**        | **Description**                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------- |
| Use Case ID      | UC-01                                                                                                             |
| Use Case Name    | User Login                                                                                                        |
| Actor            | Student / Faculty / Administrator                                                                                 |
| Preconditions    | User must be registered in the system                                                                             |
| Main Flow        | 1. User enters username and password <br> 2. System validates credentials <br> 3. User is redirected to dashboard |
| Alternative Flow | If credentials are invalid, error message is displayed                                                            |
| Postconditions   | User is successfully logged in                                                                                    |

# Use Case 2: Enter Marks

| **Field**        | **Description**                                                                                |
| ---------------- | ---------------------------------------------------------------------------------------------- |
| Use Case ID      | UC-02                                                                                          |
| Use Case Name    | Enter Marks                                                                                    |
| Actor            | Faculty                                                                                        |
| Preconditions    | Faculty must be logged in                                                                      |
| Main Flow        | 1. Faculty selects student and subject <br> 2. Faculty enters marks <br> 3. System saves marks |
| Alternative Flow | If invalid marks are entered, system asks for correction                                       |
| Postconditions   | Marks are stored successfully                                                                  |

# Use Case 3: View Results

| **Field**        | **Description**                                             |
| ---------------- | ----------------------------------------------------------- |
| Use Case ID      | UC-03                                                       |
| Use Case Name    | View Results                                                |
| Actor            | Student                                                     |
| Preconditions    | Student must be logged in and results published             |
| Main Flow        | 1. Student selects semester <br> 2. System displays results |
| Alternative Flow | If results are not available, notification is shown         |
| Postconditions   | Student views academic results                              |

# Use Case 4: Backlog Identification

| **Field**        | **Description**                                                            |
| ---------------- | -------------------------------------------------------------------------- |
| Use Case ID      | UC-04                                                                      |
| Use Case Name    | Backlog Identification                                                     |
| Actor            | Student / Faculty                                                          |
| Preconditions    | Results must be available                                                  |
| Main Flow        | 1. System checks pass/fail status <br> 2. Backlog subjects are highlighted |
| Alternative Flow | If no backlog exists, system shows success message                         |
| Postconditions   | Backlog status is identified                                               |

# Use Case 5: Manage Users

| **Field**        | **Description**                                                  |
| ---------------- | ---------------------------------------------------------------- |
| Use Case ID      | UC-05                                                            |
| Use Case Name    | Manage Users                                                     |
| Actor            | Administrator                                                    |
| Preconditions    | Administrator must be logged in                                  |
| Main Flow        | 1. Admin adds/updates/deletes users <br> 2. System assigns roles |
| Alternative Flow | If user already exists, system alerts admin                      |
| Postconditions   | User accounts are managed successfully                           |

