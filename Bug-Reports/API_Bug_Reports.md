# API Bug Reports

## BUG-001 — Unexpected 500 Internal Server Error

**Severity:** High  
**Priority:** High  
**Testing Type:** API Testing

### Steps to Reproduce
1. Send the API request with valid test data.
2. Submit the request.
3. Observe the response.

### Expected Result
The API should process the request successfully or return an appropriate client-side validation error.

### Actual Result
The API returns HTTP 500 Internal Server Error.

### Status
Open

---

## BUG-002 — Invalid Resource Returns Unexpected Response

**Severity:** Medium  
**Priority:** Medium  
**Testing Type:** Negative Testing

### Steps to Reproduce
1. Send a request using an invalid resource ID.
2. Submit the request.
3. Observe the response.

### Expected Result
The API should return an appropriate 4xx error response.

### Actual Result
The API returns an unexpected response.

### Status
Open

---

> **Note:** All endpoint names, credentials, tokens, user information, and other confidential details have been removed or generalized for portfolio purposes.
