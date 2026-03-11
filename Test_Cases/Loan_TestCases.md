# Loan Management System Test Cases

| Test Case ID | Functionality | Test Description | Pre-Requisite | Steps to Reproduce | Expected Result | Actual Result | Status |
|---------------|--------------|-----------------|---------------|-------------------|----------------|---------------|--------|
| TC_001 | Login | Verify login with valid credentials | User should be registered | Enter valid username and password and click login | User should login successfully | | |
| TC_002 | Login | Verify login with invalid username | User should be registered | Enter invalid username and valid password | Error message should display | | |
| TC_003 | Login | Verify login with invalid password | User should be registered | Enter valid username and invalid password | Error message should display | | |
| TC_004 | Loan Application | Verify loan application submission | User should be logged in | Fill loan form and click submit | Loan request should be created | | |
| TC_005 | Loan Status | Verify loan status tracking | Loan request created | Navigate to loan status page | Loan status should display | | |
