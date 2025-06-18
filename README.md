# PyTestProject2 - UI Test Automation Framework

## Overview
This is a UI Test Automation Framework built using Selenium Webdriver and Pytest.
- Basic test scenarios
- Page Object Model (POM) design
- Reusable fixtures
- HTML reporting using 'pytest-html'

## Tech Stack
  - Python
  - Pytest
  - Selenium WebDriver
  - pytest-html for reporting
 
## Project Structure
- 'DemoFirstTest/' -> Initial test examples
- 'DemoPytest/' -> Assertions and marker-based test sets
- 'pages/' -> Page Object Model (login, account pages)
- 'tests/' -> Test classes and Pytest methods
- 'utilities/' -> Reusable components (data, locators)
- 'conftest.py' -> Shared test fixtures
- 'pytest.ini' -> Pytest config with markers and options

## How to Run the Tests
1. Install dependencies: 'pip install -r requirements.txt'
2. Run all tests with verbose output and HTML report (pytest.ini file setup)
3. To generate HTML report manually: 'pytest --html=AutomationPytestReport.html'

## Sample Tests Covered
- Message form submission test
- Gender + age selection test
- Product Search validation test
- Login test with order history check

## Known Test Behavior Notes
This project intentionally includes a mix of:
- Hard assertion failures (e.g., 'assert 20 == 10')
- Soft assertion examples
- Skipped tests and '@pytest.mark.xfail(strict=True)' decorators
- Occasional Selenium timing failures (due to dynamic elements in public demo sites)
These are left in place to simulate real-world debugging, failure handling, and test
reporting for educational/demo purposes. Most failures are intentional and reflect
controlled learning outcomes from the original tutorial.


## Reports
  Sample output reports:
  - 'AutomationPytestReport.html'
 
## Author
  Sameer Siddiqui - [GitHub Profile](https://github.com/SameerS-Project/PyTestProject2)
