# 🧪 Manual Testing Project – SauceDemo

## 📌 Project Overview

This project is a **Manual Software Testing project** performed on the **SauceDemo web application**.

The objective of this project is to demonstrate the complete manual testing process, including requirement analysis, test planning, test case design, defect management, test execution, and test summary reporting.

The complete testing documentation is maintained in **one Excel workbook**:

📄 **Manual_Testing_Dhruva.xlsx**

---

## 🌐 Application Under Test

**Application:** SauceDemo / Swag Labs
**URL:** https://www.saucedemo.com/

SauceDemo is a demo e-commerce web application used for practicing software testing concepts.

---

## 🎯 Project Objective

The main objectives of this project are:

* Understand and analyze application requirements.
* Identify functional and non-functional testing requirements.
* Prepare a professional test plan.
* Design detailed manual test cases.
* Execute test scenarios manually.
* Identify and document defects.
* Understand the bug life cycle.
* Perform retesting and regression testing.
* Prepare a test execution summary and final test report.
* Demonstrate an end-to-end e-commerce testing workflow.

---

# 📊 Excel Workbook

All manual testing documentation is combined into **one Excel file**:

### `Manual_Testing_Dhruva.xlsx`

The workbook contains the following sheets:

| Sheet                  | Purpose                                                                 |
| ---------------------- | ----------------------------------------------------------------------- |
| **Requirements**       | Contains application requirements and testing requirements              |
| **Test Cases**         | Contains detailed manual test cases                                     |
| **Test Plan**          | Defines testing scope, approach, environment, criteria and deliverables |
| **BugCycle**           | Contains defect reporting and bug life-cycle information                |
| **Summary and Report** | Contains test execution summary, metrics and final testing report       |

---

# 📋 1. Requirements

The **Requirements** sheet contains the requirements identified for the SauceDemo application.

The requirements cover major application areas such as:

* User Login
* Authentication
* Product Listing
* Product Details
* Product Sorting
* Shopping Cart
* Add Product to Cart
* Remove Product from Cart
* Checkout
* Customer Information
* Order Overview
* Order Placement
* Order Confirmation
* Navigation
* Logout
* Application usability

The requirements are used as the foundation for designing test cases.

---

# 🧪 2. Test Cases

The **Test Cases** sheet contains detailed manual test cases designed from the identified requirements.

The test cases cover:

### 🔐 Login Module

* Valid login
* Invalid login
* Locked user login
* Empty username
* Empty password
* Invalid credentials

### 🛍️ Product Module

* Product listing
* Product details
* Product sorting
* Product information validation

### 🛒 Cart Module

* Add product to cart
* Remove product from cart
* Cart item validation
* Cart quantity and product information

### 💳 Checkout Module

* Checkout navigation
* Customer information validation
* Checkout overview
* Order placement
* Order confirmation

### 🧭 Navigation Module

* Menu navigation
* Logout
* Reset application state

### 🔄 End-to-End Testing

The complete customer journey is also covered:

**Login → Products → Product Selection → Add to Cart → Cart → Checkout → Order Overview → Place Order → Confirmation → Logout**

---

# 📝 3. Test Plan

The **Test Plan** sheet defines the overall testing strategy for the project.

It includes:

* Testing objective
* Application under test
* Scope of testing
* Out of scope
* Testing approach
* Test environment
* Test data
* Entry criteria
* Exit criteria
* Testing techniques
* Defect management process
* Severity and priority
* Testing deliverables
* Future automation scope

### Testing Types

The project focuses mainly on:

* Functional Testing
* UI Testing
* Integration Flow Testing
* End-to-End Testing
* Positive Testing
* Negative Testing
* Boundary/Validation Testing
* Regression Testing
* Retesting
* Exploratory Testing

---

# 🐞 4. Bug Cycle

The **BugCycle** sheet demonstrates the defect management process.

The general bug life cycle followed in the project is:

```text
New
  ↓
Assigned
  ↓
In Progress
  ↓
Fixed
  ↓
Retest
  ↓
Closed
```

If the defect is not fixed correctly:

```text
Retest
   ↓
Reopened
   ↓
Fixed
   ↓
Retest
   ↓
Closed
```

## Bug Report Information

Defects can be documented using information such as:

* Bug ID
* Module
* Bug Title
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Bug Life Cycle Status
* Execution Information
* Reported By

---

# 📊 5. Summary and Report

The **Summary and Report** sheet provides the overall testing result and project summary.

It can be used to record:

* Total test cases
* Executed test cases
* Passed test cases
* Failed test cases
* Blocked test cases
* Not executed test cases
* Defects identified
* Testing observations
* Overall testing conclusion

The final report provides a high-level view of the testing performed on the SauceDemo application.

> **Note:** Test results should be updated based on actual manual execution. No test result should be marked as Passed or Failed without executing the corresponding test case.

---

# 🔄 Testing Process

The complete testing workflow followed in this project is:

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Scenario Identification
        ↓
Test Case Design
        ↓
Test Data Preparation
        ↓
Manual Test Execution
        ↓
Defect Identification
        ↓
Bug Reporting
        ↓
Bug Life Cycle
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Summary Report
```

---

# 🧪 Sample Test Data

### Standard User

```text
Username: standard_user
Password: secret_sauce
```

### Locked User

```text
Username: locked_out_user
Password: secret_sauce
```

These credentials are provided by the SauceDemo demo application for testing purposes.

---

# 💻 Test Environment

| Parameter        | Details                        |
| ---------------- | ------------------------------ |
| Application      | SauceDemo                      |
| Testing Type     | Manual Testing                 |
| Operating System | Windows                        |
| Browser          | Google Chrome / Microsoft Edge |
| Application Type | Web Application                |
| Testing Approach | Manual Functional Testing      |
| Documentation    | Microsoft Excel                |

---

# 📸 Test Evidence

Screenshots can be captured during actual test execution and stored in the GitHub repository.

Recommended structure:

```text
Screenshots/
├── Login/
├── Products/
├── Cart/
├── Checkout/
└── Bugs/
```

Screenshots should represent **actual test execution evidence**.

---


# 🔗 Traceability

The project follows traceability between requirements and test cases.

```text
Requirements
      ↓
Test Cases
      ↓
Test Execution
      ↓
Defects
      ↓
Retesting
      ↓
Final Test Summary
```

This helps ensure that the identified requirements are properly tested and that defects can be traced back to the relevant functionality.

---

# 🚀 Future Scope

This manual testing project can later be extended into an automation testing project.

Planned future technologies:

* Selenium WebDriver
* Java
* TestNG
* Maven
* Page Object Model (POM)
* API Testing
* SQL Testing
* Git & GitHub
* CI/CD
* Jenkins

The same test cases can be reused as the foundation for future automation testing.

---

# 🎓 Skills Demonstrated

This project demonstrates knowledge of:

* Manual Testing
* Software Testing Life Cycle (STLC)
* Test Case Design
* Test Scenario Design
* Requirement Analysis
* Test Planning
* Functional Testing
* Positive Testing
* Negative Testing
* Regression Testing
* Retesting
* Exploratory Testing
* Defect Reporting
* Bug Life Cycle
* Severity vs Priority
* End-to-End Testing
* Test Execution
* Test Reporting
* Requirement Traceability

---

# 👨‍💻 Author

**Dhruva Gohil**

**Profile:** BSc Computer Science Graduate | Software Testing / QA Fresher

---

# ⚠️ Disclaimer

SauceDemo is used as a **demo application for learning, practice, and portfolio testing purposes**.

This project is created to demonstrate software testing knowledge and practical QA documentation skills.

---

## ⭐ Project Outcome

This project demonstrates a complete manual testing workflow from:

**Requirement Analysis → Test Planning → Test Case Design → Test Execution → Defect Management → Retesting → Regression Testing → Test Summary**

The complete manual testing documentation is maintained in **one Excel workbook:**

**`Manual_Testing_Dhruva.xlsx`**
