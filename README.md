# Test Cases for cmsMinds Website

## 🧪 **Test Case Overview**
This document outlines the test cases for verifying the functionality, performance, and security of the **cmsMinds** website. It includes functional tests, regression tests, and performance checks to ensure the website's quality and usability.

---

## 🔍 **Test Suite Categories**
- **Functional Tests:** Verifying that the core features of the cmsMinds website function as expected.
- **Regression Tests:** Ensuring that recent changes to the website do not affect its existing functionality.
- **Performance Tests:** Ensuring that the website loads quickly and performs well under various conditions.
- **Usability Tests:** Ensuring that the website is user-friendly and provides a positive experience.
- **Security Tests:** Ensuring that the website is secure from common vulnerabilities.

---

## 📋 **Test Case Template**
Each test case is structured as follows:

1. **Test Case ID:** Unique identifier for the test case.
2. **Test Case Title:** A brief description of the test case.
3. **Preconditions:** Any setup required before executing the test case.
4. **Test Steps:** Step-by-step instructions for performing the test.
5. **Expected Result:** The expected outcome of the test.
6. **Actual Result:** The outcome of the test when executed (usually filled during testing).
7. **Status:** The result of the test (Pass/Fail).
8. **Priority:** The priority level (Low, Medium, High).
9. **Notes:** Any additional information or comments.

---

## 📚 **Test Cases List**

### 1. **Home Page Load Time**

- **Test Case ID:** TC001
- **Test Case Title:** Verify the home page loads within 3 seconds.
- **Preconditions:** User is not logged in and is visiting the home page.
- **Test Steps:**
  1. Navigate to the cmsMinds homepage.
  2. Start a timer as the page begins loading.
  3. Stop the timer once the page has fully loaded.
- **Expected Result:** The page should load within 3 seconds.
- **Actual Result:** _To be filled during test execution_
- **Status:** _Pass/Fail_
- **Priority:** High
- **Notes:** Test on different browsers and devices.

---

### 2. **Contact Form Submission**

- **Test Case ID:** TC002
- **Test Case Title:** Verify that the contact form submits successfully with valid input.
- **Preconditions:** User is on the "Contact Us" page.
- **Test Steps:**
  1. Navigate to the contact form.
  2. Enter a valid name, email, and message.
  3. Click the "Submit" button.
- **Expected Result:** The form should submit successfully, and a success message should appear.
- **Actual Result:** _To be filled during test execution_
- **Status:** _Pass/Fail_
- **Priority:** High
- **Notes:** Ensure the form fields are validated before submission.

---

### 3. **Login Functionality**

- **Test Case ID:** TC003
- **Test Case Title:** Verify that the login functionality works with valid credentials.
- **Preconditions:** User has valid credentials for the cmsMinds website.
- **Test Steps:**
  1. Navigate to the login page.
  2. Enter valid credentials (username and password).
  3. Click the "Login" button.
- **Expected Result:** User is successfully logged in and redirected to the dashboard page.
- **Actual Result:** _To be filled during test execution_
- **Status:** _Pass/Fail_
- **Priority:** High
- **Notes:** Test for both admin and regular user roles.

---

### 4. **Responsive Design Check**

- **Test Case ID:** TC004
- **Test Case Title:** Verify that the cmsMinds website is responsive across different devices.
- **Preconditions:** User is on the homepage.
- **Test Steps:**
  1. Open the website on different devices (desktop, tablet, mobile).
  2. Ensure that the layout adjusts correctly on each device.
  3. Check if images and buttons scale properly.
- **Expected Result:** The website should adjust its layout based on the device screen size, ensuring a seamless user experience.
- **Actual Result:** _To be filled during test execution_
- **Status:** _Pass/Fail_
- **Priority:** Medium
- **Notes:** Test across popular browsers (Chrome, Firefox, Safari).

---

### 5. **404 Error Page**

- **Test Case ID:** TC005
- **Test Case Title:** Verify the 404 error page is shown when accessing a non-existent URL.
- **Preconditions:** User is logged out or not logged in.
- **Test Steps:**
  1. Access a URL that does not exist on the cmsMinds website.
  2. Observe the page response.
- **Expected Result:** The page should display a custom 404 error page with a message like "Page Not Found."
- **Actual Result:** _To be filled during test execution_
- **Status:** _Pass/Fail_
- **Priority:** Low
- **Notes:** Ensure that the error page is informative and user-friendly.

---

## 🛠 **Test Environment**
- **Operating System:** Windows 10, macOS 11
- **Browsers:** Chrome, Firefox, Safari
- **Devices:** Desktop, Tablet, Mobile
- **Tools Used:** Selenium WebDriver, JIRA, TestNG, Jenkins

---

## 🚀 **Test Execution**
- **Frequency:** The test cases are executed after every code change and during release cycles.
- **Automation:** Automated tests are run every night via Jenkins to check regression.

---

## 📝 **Test Reporting**
Test results are tracked using **JIRA**. Each test case is logged as a task, and the test status (Pass/Fail) is updated accordingly.

---

## 💡 **Test Case Maintenance**
Test cases will be updated after every release or significant change to the cmsMinds website. This ensures that the test suite reflects the current functionality and business requirements.

---

## 📚 **Additional Resources**
- [Selenium WebDriver Documentation](https://www.selenium.dev/documentation/en/webdriver/)
- [JIRA for Test Case Management](https://www.atlassian.com/software/jira)

---

## 📞 **Contact**
For any queries related to test cases or issues, please contact:
- **QA :** [Harsh Sharma]
- **Email:** [Harshsharmaqa@gmail.com]


---

© 2025 **cmsMinds** | *Quality Assurance at its Best* 🚀
