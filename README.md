# Budget Project
This project is a simple budget tracker for anyone to use. It is written using Java and JavaFX.

## Tech Stack
Java, JavaFX, Maven, SQLite, JUnit 5, MVC architecture

## Demo Video
Demo video located in /assets/DEMO_VIDEO.mp4  

## Setup

### Prerequisites
- JDK 17+
- Maven

### Run
```bash
git clone https://github.com/BDaniel1/budget-project.git
cd budget-project
mvn javafx:run
```

## Features
* CRUD operations for budget entries
* Summary dashboard with income, expenses, and net balance
* Pie chart expense visualization
* Input validation for transaction forms
* Transaction list with sorting and filtering
* SQLite persistence for local data storage

## Known Issues / Limitations
* Some exceptions currently log stack traces instead of user-friendly messages
* Sorting and filtering preferences are not saved between runs
* No user authentication implemented
* FXML built with JavaFX API 23.0.1 while runtime is 17.0.9 (no observed issues)

## Testing
Unit tests written with JUnit.
See the test report: [Test Report](TEST_REPORT.md).  
JUnit was used for all unit tests.

## Author Information
**Bryan Daniel**  
CompSci & Cybersec Student  
GitHub: https://github.com/BDaniel1
