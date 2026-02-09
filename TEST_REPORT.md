# Test Report

This document summarizes the unit testing performed for the Budget Project.

## Testing Environment
- JUnit 5.x
- Java 17
- Windows 11
- SQLite

## Test Coverage

### Controllers
| Test # | Description                             | Result | Comments                               |
|--------|-----------------------------------------|--------|----------------------------------------|
| 001    | Entry form controller constructor       | Pass   | Constructor initializes controller     |
| 002    | Entry form passTransactionService       | Pass   | Service injection verified             |
| 003    | Summary page controller constructor     | Pass   | Constructor initializes controller     |
| 004    | Summary page passTransactionService     | Pass   | Service injection verified             |
| 005    | Transaction list controller constructor | Pass   | Constructor initializes controller     |

### Models
| Test # | Description              | Result | Comments                              |
|--------|--------------------------|--------|---------------------------------------|
| 006    | Transaction constructor  | Pass   | Model instantiates correctly          |
| 007    | LocalDate property       | Pass   | Getter returns expected value         |
| 008    | Amount property          | Pass   | Getter returns expected value         |
| 009    | Description property     | Pass   | Getter returns expected value         |
| 010    | Category property        | Pass   | Getter returns expected value         |
| 011    | Type property            | Pass   | Getter returns expected value         |

### Services
| Test # | Description                                     | Result | Comments                                      |
|--------|-------------------------------------------------|--------|-----------------------------------------------|
| 012    | Database read/add/delete                        | Pass   | CRUD operations verified                      |
| 013    | Database read/update/delete                     | Pass   | CRUD operations verified                      |
| 014    | Validate valid date                             | Pass   | Input validation successful                   |
| 015    | Validate invalid date                           | Pass   | Invalid input rejected                        |
| 016    | Validate valid amount                           | Pass   | Input validation successful                   |
| 017    | Validate invalid amount                         | Pass   | Invalid input rejected                        |
| 018    | Income total calculation                        | Pass   | Correct totals returned                       |
| 019    | Expense total calculation                       | Pass   | Correct totals returned                       |
| 020    | Net balance calculation                         | Pass   | Correct totals returned                       |
| 021    | Sort functionality                              | Pass   | Sorting behaves as expected                   |
| 022    | Filter functionality                            | Pass   | Filtering behaves as expected                 |

## Build / Test Output
![Test Console Output](assets/test_log.png)

## Known Issues
No known defects identified during testing.  
Refer to README.md for documented limitations.

