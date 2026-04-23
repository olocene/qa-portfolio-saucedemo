# Test Plan – SauceDemo Login Testing

## 1. Objective
The objective of this test plan is to verify the login functionality of the SauceDemo application and ensure that users can authenticate correctly according to expected business rules.

## 2. Scope
This test plan covers the following login scenarios:

- Login with valid credentials
- Login with invalid credentials
- Login with locked user
- Detection and documentation of unexpected behaviors during login

## 3. Out of Scope
The following areas are not covered in this phase:

- Product browsing
- Add to cart
- Checkout process
- Performance testing
- Cross-browser testing
- Mobile responsiveness

## 4. Test Items
Application under test:
- SauceDemo
- URL: https://www.saucedemo.com/

## 5. Test Approach
Manual testing was performed by executing predefined test cases and comparing actual results with expected results.

The following techniques were applied:
- Positive testing
- Negative testing
- Basic error handling validation
- Exploratory observation for unexpected behaviors

## 6. Entry Criteria
Testing can start when:
- The application is reachable
- Login page is available
- Test credentials are known

## 7. Exit Criteria
Testing is considered complete when:
- All planned login test cases are executed
- Results are documented
- Bugs or anomalies are reported
- Evidence is collected when needed

## 8. Test Environment
- Operating System: Windows
- Browser: Google Chrome
- Test Type: Manual testing

## 9. Test Data
Credentials used during testing:

- Valid user:
  - Username: standard_user
  - Password: secret_sauce

- Invalid login:
  - Username: standard_user
  - Password: wrong_password

- Locked user:
  - Username: locked_out_user
  - Password: secret_sauce

## 10. Deliverables
The following deliverables are included in this project:

- Test cases
- Test execution results
- Bug reports
- Screenshots
- README documentation

## 11. Risks
Possible risks related to this project:

- Demo environment may contain browser-related behaviors
- Some anomalies may not belong to the application itself
- Limited scope may not reveal deeper functional defects

## 12. Defect Management
Defects identified during execution are documented in:
- Jira project
- GitHub bug-reports folder

Each defect includes:
- Title
- Description
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Screenshot when applicable

## 13. Summary
This test plan provides a structured approach to validate the login functionality of SauceDemo and document test evidence in a professional QA portfolio format.
