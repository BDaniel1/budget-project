# Budget Project
A desktop budget tracker built with Java and JavaFX for managing personal financial transactions with summaries and visualizations.

## Tech Stack
Java, JavaFX, Maven, SQLite, JUnit 5

## Project Structure
- `src/main/java/com/brdaniel/budgetproject/` - Application source (MVC-style structure)
  - `controllers/` - JavaFX controllers
  - `models/` - Domain models (e.g., `Transaction`)
  - `services/` - Business logic and persistence services
  - `view/` - UI helper windows (confirmation/error dialogs)
- `src/main/resources/view/` - JavaFX FXML views
- `src/test/java/com/brdaniel/budgetproject/` - Unit tests (JUnit)
- `pom.xml` - Maven build configuration
- `assets/` - Demo video and test output screenshot
- `TEST_REPORT.md` - Unit test summary

## Demo
A short walkthrough of the application: [Demo Video](assets/DEMO_VIDEO.mp4) 

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
- CRUD operations for budget entries
- Summary dashboard with income, expenses, and net balance
- Pie chart expense visualization
- Input validation for transaction forms
- Transaction list with sorting and filtering
- SQLite persistence for local data storage

## Known Issues / Limitations
- Some exceptions currently log stack traces instead of user-friendly messages
- Sorting and filtering preferences are not saved between runs
- No user authentication implemented
- FXML built with JavaFX API 23.0.1 while runtime is 17.0.9 (no observed issues)

## Testing
Unit tests written with JUnit.
See the test report: [Test Report](TEST_REPORT.md).  

## Author Information
**Bryan Daniel**  
CompSci & Cybersec Student  
GitHub: https://github.com/BDaniel1
