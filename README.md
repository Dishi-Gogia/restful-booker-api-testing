# 🧪 Restful Booker API Testing Portfolio

A comprehensive Manual API Testing portfolio demonstrating real-world API validation practices using Postman, including test planning, test design, execution, defect management, and API workflow validation across a hotel booking application.

---

## 🎯 Overview

API testing is a critical component of modern software quality assurance.

Validating APIs ensures that applications communicate correctly, business rules are enforced, and data flows reliably across systems.

This repository showcases a complete Manual API Testing lifecycle using the Restful Booker application and industry-standard QA documentation.

✔️ Validate API functionality and business workflows

✔️ Verify request and response integrity

✔️ Test authentication and authorization mechanisms

✔️ Validate status codes, headers, and response structures

✔️ Execute positive and negative test scenarios

✔️ Capture defects and execution evidence

✔️ Produce enterprise-grade QA artifacts

---

## 📚 API Modules Covered

### 🔐 Authentication API

Validate token generation and authentication behavior

* Valid credentials
* Invalid credentials
* Blank credentials
* Response validation
* Response time validation
* Unsupported method validation

### 🏨 Create Booking API

Validate booking creation workflows

* Valid booking creation
* Mandatory field validation
* Null and blank value validation
* Invalid date scenarios
* Special character testing
* Boundary and negative testing

### 🔍 Get Booking API

Validate booking retrieval functionality

* Valid booking retrieval
* Invalid booking IDs
* Negative and alphanumeric IDs
* Response structure validation
* Header validation

### ✏️ Update Booking API

Validate booking modification workflows

* Authorized updates
* Unauthorized access validation
* Invalid token scenarios
* Data persistence verification
* Response validation

### ⚡ Partial Update API

Validate selective field updates

* Partial record updates
* Authentication validation
* Business data verification

### 🗑️ Delete Booking API

Validate booking deletion functionality

* Valid deletion
* Invalid deletion attempts
* Authorization checks
* Post-deletion validation

### 🔎 Search Booking API

Validate booking search capabilities

* Search by firstname
* Search by lastname
* Search by dates
* Multi-filter search validation
* Response validation

---

## 🧠 Testing Areas Covered

### 🔹 Functional Testing

Validate API business functionality against requirements.

### 🔹 Positive Testing

Verify successful execution using valid requests.

### 🔹 Negative Testing

Validate error handling using invalid inputs and conditions.

### 🔹 Authorization Testing

Validate token-based access controls.

### 🔹 Status Code Validation

Verify APIs return appropriate HTTP response codes.

### 🔹 Response Validation

Validate response body structure, fields, and data integrity.

### 🔹 Header Validation

Verify API response headers and content types.

### 🔹 Response Time Validation

Validate API performance against expected response thresholds.

---

## 📋 Test Artifacts Included

✔️ Test Plan

✔️ Test Scenarios (64 Scenarios)

✔️ Detailed Test Cases

✔️ Postman Collection

✔️ Execution Report

✔️ Defect Log

✔️ Test Summary Report

✔️ Screenshots & Evidence

---

## 📊 Test Coverage Summary

| Area                   | Coverage     |
| ---------------------- | ------------ |
| Authentication         | 8 Scenarios  |
| Create Booking         | 13 Scenarios |
| Get Booking            | 8 Scenarios  |
| Update Booking         | 9 Scenarios  |
| Partial Update         | 3 Scenarios  |
| Delete Booking         | 8 Scenarios  |
| Search Booking         | 8 Scenarios  |
| Status Code Validation | 4 Scenarios  |
| Other API Validations  | 4 Scenarios  |

**Total Coverage:** 64 Test Scenarios

---

## 📂 Repository Structure

```text
restful-booker-api-testing
│
├── TestPlan
├── TestScenarios
├── TestCases
├── PostmanCollection
├── ExecutionReports
├── DefectReports
├── TestSummaryReport
├── Screenshots
└── README.md
```

---

## 💡 Sample API Request

### Generate Authentication Token

```json
POST /auth

{
  "username": "admin",
  "password": "password123"
}
```

### Sample Response

```json
{
  "token": "abc123xyz"
}
```

---

## 🔥 Key Highlights

✔️ Real-world Manual API Testing Portfolio

✔️ End-to-End API Validation Lifecycle

✔️ Enterprise QA Documentation Approach

✔️ Postman-Based Testing Framework

✔️ Positive & Negative Test Coverage

✔️ Defect Tracking and Reporting

✔️ Suitable for QA Engineers, Test Leads, and QA Managers

✔️ Demonstrates API Testing Best Practices

---

## 🚀 Future Enhancements

🔹 Newman Execution Reports

🔹 REST Assured Automation Framework

🔹 CI/CD Pipeline Integration

🔹 API Schema Validation

🔹 Data-Driven API Testing

🔹 API Automation Reporting

---

## 🔗 Related Work

This repository complements my other QA repositories:

👉 Selenium Framework:
https://github.com/Dishi-Gogia/selenium-java-hybrid-framework

👉 Java for QA Engineers:
https://github.com/Dishi-Gogia/Java-for-QA-Engineers

👉 SQL Validation Queries:
https://github.com/Dishi-Gogia/sql-validation-queries

---

## 👩‍💻 Author

**Dishi Gogia**

Senior QA Manager | Quality Engineering | API Testing | Automation Testing | Salesforce CRM | Oracle CPQ (Q2C) | Agile Delivery

---

⭐ If this repository helps, consider giving it a star!
