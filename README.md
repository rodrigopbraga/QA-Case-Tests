# Software Quality Assurance – Test Cases

This repository contains a collection of **manual test cases** created for both **Web** and **API** testing as part of a Software Quality Assurance project.

The objective is to demonstrate the application of software testing techniques, including **Equivalence Partitioning**, **Boundary Value Analysis**, validation of functional requirements, and defect reporting.

---

## 📋 Project Overview

This project covers two testing scopes:

- **Web Application Testing**
  - Functional validation of the Urban Scooter ordering form.
  - Input field validation using Equivalence Classes and Boundary Values.
  - Cross-browser execution.
  - Test execution results documentation.

- **API Testing**
  - Validation of the `POST /api/v1/courier` endpoint.
  - Positive and negative scenarios.
  - Request body validation.
  - HTTP status code verification.
  - Defect identification and Jira references.

---

## 📂 Repository Structure

```
.
├── QA-Case-Tests.xlsx
└── README.md
```

The Excel workbook contains three worksheets:

| Worksheet | Description |
|-----------|-------------|
| **Project Info** | Project metadata |
| **Web Test Cases** | Functional test cases for the Urban Scooter order form |
| **API Test Cases** | API validation scenarios for Courier creation |

---

## 🧪 Testing Techniques Used

- Equivalence Partitioning
- Boundary Value Analysis (BVA)
- Positive Testing
- Negative Testing
- Functional Testing
- Input Validation
- API Testing
- Manual Testing
- Defect Reporting

---

## 🌐 Web Testing

The web scenarios validate form fields such as **First Name**, including:

- Minimum valid length
- Maximum valid length
- Below minimum values
- Above maximum values
- Empty field validation
- Numeric characters
- Special characters
- Hyphen and space acceptance

Each test case contains:

- Test ID
- Test description
- Preconditions
- Test steps
- Equivalence class
- Boundary values
- Test data
- Expected result
- Actual result
- Execution status
- Browser execution results

Browsers tested:

- Google Chrome
- Opera

---

## 🔌 API Testing

The API scenarios validate the endpoint:

```
POST /api/v1/courier
```

Covered scenarios include:

- Valid login length
- Invalid login length
- Empty login
- Maximum accepted length
- Above maximum length
- Invalid characters
- Expected HTTP responses
- Actual responses
- Defect tracking

---

## 🐞 Defect Reporting

Whenever expected behavior differs from the actual behavior, defects are documented with their corresponding Jira reference.

Example:

| Test Case | Expected | Actual | Status |
|-----------|----------|--------|--------|
| Login with 1 character | 409 Invalid Login | 201 Created | ❌ Failed |

---

## 📊 Test Case Structure

Each test case follows the standard QA format:

- Test ID
- Title
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Execution Status
- Bug Reference (if applicable)

---

## 🎯 Purpose

This repository demonstrates practical knowledge of:

- Software Quality Assurance
- Test Case Design
- Manual Testing
- API Validation
- Functional Testing
- Defect Identification
- Test Documentation

---

## 🛠 Tools

- Microsoft Excel
- Jira (Bug Tracking)
- REST API
- Web Browser Testing

---

## 📈 Skills Demonstrated

- Manual QA
- Test Planning
- Functional Testing
- API Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Test Documentation
- Bug Reporting
- Cross-browser Testing

---

## 📄 License

This project is intended for educational purposes and portfolio demonstration.
