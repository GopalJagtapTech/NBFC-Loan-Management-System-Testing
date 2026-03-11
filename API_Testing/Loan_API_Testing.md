# API Testing

API 1 – Login API

Endpoint:
/api/login

Method:
POST

Request:
{
 "username":"testuser",
 "password":"12345"
}

Expected Response:
200 OK

---

API 2 – Loan Application API

Endpoint:
/api/loan/apply

Method:
POST

Expected Result:
Loan created successfully

---

API 3 – Loan Status API

Endpoint:
/api/loan/status

Method:
GET

Expected Result:
Loan status returned
