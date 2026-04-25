# API Test Cases

## TC_API_001 – GET Users
Request: GET /users  
Expected:
- Status: 200
- JSON array returned

---

## TC_API_002 – Invalid Endpoint
Request: GET /invalid  
Expected:
- Status: 404

---

## TC_API_003 – Response Time
Expected:
< 2 seconds

---

## TC_API_004 – Data Validation
Expected:
Fields: id, name, email present
