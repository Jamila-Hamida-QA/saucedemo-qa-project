Test Plan - SauceDemo

# 1. Introduction
This Test Plan defines the scope, approach, resources, and schedule for testing the SauceDemo application, a demo e-commerce platform used for QA practice.

The objective is to ensure that all critical functionalities of the application work as expected.

# 2. Objective
- Validate the main functionalities of the application.
- Ensure the stability of user workflows.
- Identify defects early in the testing process.
- Ensure a good user experience across browsers.

# 3. Scope of Testing

### In Scope:
- User Login.
- Product listing.
- Product sorting and filtering.
- Add to cart functionality.
- Shopping cart validation.
- Checkout process.
- Logout functionality.

### Out of Scope:
- Backend/database testing.
- Performance/load testing.
- Security penetration testing.

# 4. Test Items
- Login Page.
- Products Page.
- Cart Page.
- Checkout Page.
- Logout Functionality.

# 5. Test Approach

### Manual Testing:
- Execute predefined test cases.
- Perform exploratory testing.
- Validate UI and functional behavior.
- Report defects with screenshots.

### Automation Testing:
- Use Playwright for automation.
- Automate critical flows:
  - Login
  - Add to cart
  - Checkout process
- Apply Page Object Model (POM)

---

# 6. Test Environment
- Application: https://www.saucedemo.com/
- Browsers: Chrome, Firefox, Edge.
- Operating System: Windows.
- Tools:
  - Jira (bug tracking).
  - Playwright (automation).
  - GitHub (version control).

# 7. Test Data
- standard_user / secret_sauce.
- locked_out_user.
- problem_user.
- performance_glitch_user.

# 8. Roles and Responsibilities
- QA Engineer: Test design and execution.
- Automation QA: Script development using Playwright.
- Developer: Fixing defects.
- Reviewer: Validate test cases and reports.

# 9. Entry Criteria
- Application is deployed and accessible.
- Test cases are ready.
- Test environment is stable.
- Test data is prepared.

# 10. Exit Criteria
- All critical test cases executed.
- No blocker or critical defects open.
- Test execution report completed.
- Test summary report approved.

# 11. Risks and Mitigation

### Risks:
- Application instability.
- UI changes without notice.
- Limited test environment control.

### Mitigation:
- Regular test updates.
- Regression testing after changes.
- Clear communication with stakeholders.

## 12. Deliverables
- Test Plan.
- Test Cases.
- Bug Reports.
- Test Execution Report.
- Test Summary Report.
- Automation Scripts (Playwright).
