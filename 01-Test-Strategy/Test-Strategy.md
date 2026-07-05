Test Strategy - SauceDemo

# 1. Introduction
This document defines the test strategy for the SauceDemo application, a demo e-commerce web application used for QA practice and test automation.

The goal is to ensure the quality, functionality, and reliability of the application through structured manual and automated testing.

# 2. Objectives
- Validate all functional requirements of the application.
- Ensure critical user flows work correctly (login, product selection, checkout).
- Identify defects early in the development lifecycle.
- Ensure UI behaves correctly across different browsers.
- Support regression testing for stable releases.

# 3. Scope

### In Scope:
- Login functionality.
- Product catalog.
- Product sorting and filtering.
- Shopping cart.
- Checkout process.
- Logout functionality.

### Out of Scope:
- Backend/database validation.
- Performance and load testing.
- Security penetration testing.

# 4. Test Approach

### Manual Testing
- Execute test cases using Excel or test management tools.
- Validate UI behavior and business rules.
- Perform exploratory testing.
- Log defects with clear reproduction steps.

### Automation Testing
- Use Playwright for UI automation.
- Automate critical workflows:
  - Login
  - Add to cart
  - Checkout process
- Follow Page Object Model (POM) design pattern.

# 5. Types of Testing
- Functional Testing.
- Regression Testing.
- Smoke Testing.
- UI Testing.
- Negative Testing.
- Cross-browser Testing.

# 6. Test Environment
- Application: https://www.saucedemo.com/
- Browsers: Chrome, Firefox, Edge.
- Operating System: Windows.
- Tools: Playwright, Postman, Excel, GitHub.

# 7. Test Data
- standard_user / secret_sauce
- locked_out_user
- problem_user
- performance_glitch_user


# 8. Entry Criteria
- Application is available and stable.
- Test cases are prepared and reviewed.
- Test environment is accessible.
- Test data is ready.


# 9. Exit Criteria
- All critical test cases executed successfully.
- No open critical or blocker defects.
- Test execution report completed.
- Test summary report delivered.

# 10. Risks and Assumptions

### Risks:
- Application instability or downtime.
- UI changes without prior notice.
- Limited control over test environment.

### Assumptions:
- Test environment is stable during execution.
- Test data remains valid.
- Application behaves consistently across browsers.

## 11. Deliverables
- Test Strategy Document.
- Test Plan.
- Test Cases.
- Bug Reports.
- Test Execution Report.
- Test Summary Report.
- Automation Scripts (Playwright).
