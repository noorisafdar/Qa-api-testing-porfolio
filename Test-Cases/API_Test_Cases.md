# API Test Cases

## Authentication

| Test Case ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| TC-001 | Verify API request with valid authentication | Request is accepted and returns the expected response | Pass |
| TC-002 | Verify API request with invalid authentication | API rejects the request with an appropriate authentication error | Pass |
| TC-003 | Verify API request without authentication | API rejects the request | Pass |

## GET API Testing

| Test Case ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| TC-004 | Verify GET request with valid resource ID | API returns the requested resource | Pass |
| TC-005 | Verify GET request with invalid resource ID | API returns an appropriate error response | Pass |
| TC-006 | Verify GET request for an unavailable resource | API handles the request appropriately | Pass |

## POST API Testing

| Test Case ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| TC-007 | Verify POST request with valid data | Resource is created successfully | Pass |
| TC-008 | Verify POST request with missing required data | API returns a validation error | Pass |
| TC-009 | Verify POST request with invalid data | API rejects invalid input | Pass |

## Negative Testing

| Test Case ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| TC-010 | Send invalid request data | API returns an appropriate error response | Pass |
| TC-011 | Send request with missing required fields | API returns a validation error | Pass |
| TC-012 | Send request using an invalid endpoint | API returns an appropriate error response | Pass |

> All examples are sanitized for portfolio purposes. No production credentials, tokens, passwords, or confidential data are included.
