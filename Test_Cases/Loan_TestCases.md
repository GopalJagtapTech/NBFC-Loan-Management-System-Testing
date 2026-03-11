| Test Case ID | Module | Test Description | Precondition | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC_001 | Login | Verify login with valid credentials | User registered | Enter valid username & password | User logged in successfully | | |
| TC_002 | Login | Verify login with invalid username | User registered | Enter invalid username | Error message displayed | | |
| TC_003 | Login | Verify login with invalid password | User registered | Enter invalid password | Error message displayed | | |
| TC_004 | Login | Verify login with blank username | NA | Leave username blank and login | Validation message displayed | | |
| TC_005 | Login | Verify login with blank password | NA | Leave password blank and login | Validation message displayed | | |
| TC_006 | Login | Verify login with both fields blank | NA | Click login without entering data | Validation message displayed | | |
| TC_007 | Login | Verify password masking | Login page open | Enter password | Password hidden with dots | | |
| TC_008 | Login | Verify forgot password link | Login page open | Click forgot password | Reset page displayed | | |
| TC_009 | Login | Verify login with inactive user | User inactive | Attempt login | Access denied message | | |
| TC_010 | Login | Verify session timeout | User logged in | Stay idle for long time | Session expired | | |
| TC_011 | Dashboard | Verify dashboard load | User logged in | Navigate to dashboard | Dashboard displayed | | |
| TC_012 | Dashboard | Verify welcome message | User logged in | Open dashboard | Welcome message visible | | |
| TC_013 | Dashboard | Verify navigation menu | User logged in | Check menu items | Menu items displayed | | |
| TC_014 | Dashboard | Verify user profile page | User logged in | Click profile | Profile page displayed | | |
| TC_015 | Dashboard | Verify notifications | User logged in | Click notification icon | Notifications shown | | |
| TC_016 | Loan | Verify loan application page open | User logged in | Click apply loan | Loan form opened | | |
| TC_017 | Loan | Verify loan application submission | Loan form filled | Submit loan form | Loan request created | | |
| TC_018 | Loan | Verify mandatory fields | Loan form open | Submit without filling data | Validation message | | |
| TC_019 | Loan | Verify loan amount validation | Loan form open | Enter negative amount | Error displayed | | |
| TC_020 | Loan | Verify loan tenure validation | Loan form open | Enter invalid tenure | Validation message | | |
| TC_021 | Customer | Verify add customer | User logged in | Add customer details | Customer created | | |
| TC_022 | Customer | Verify edit customer | Customer exists | Update customer info | Customer updated | | |
| TC_023 | Customer | Verify delete customer | Customer exists | Delete record | Customer deleted | | |
| TC_024 | Customer | Verify search customer | Customers available | Search by name | Customer displayed | | |
| TC_025 | Customer | Verify mobile number validation | Form open | Enter invalid mobile | Error displayed | | |
| TC_026 | Loan | Verify loan approval | Loan submitted | Approve loan | Loan approved | | |
| TC_027 | Loan | Verify loan rejection | Loan submitted | Reject loan | Loan rejected | | |
| TC_028 | Loan | Verify EMI calculation | Loan form open | Enter loan details | EMI calculated | | |
| TC_029 | Loan | Verify interest calculation | Loan form open | Enter interest rate | EMI updated | | |
| TC_030 | Loan | Verify document upload | Loan form open | Upload document | Document uploaded | | |
| TC_031 | Loan Status | Verify loan status page | Loan exists | Open loan status | Status displayed | | |
| TC_032 | Loan Status | Verify approved status | Loan approved | Check status | Approved status visible | | |
| TC_033 | Loan Status | Verify rejected status | Loan rejected | Check status | Rejected status visible | | |
| TC_034 | Loan Status | Verify pending status | Loan pending | Check status | Pending status visible | | |
| TC_035 | Loan Status | Verify loan tracking | Loan exists | Track loan | Loan details visible | | |
| TC_036 | Reports | Verify report generation | Loans exist | Generate report | Report generated | | |
| TC_037 | Reports | Verify export report | Report open | Export PDF | PDF downloaded | | |
| TC_038 | Reports | Verify filter functionality | Report page open | Apply filters | Filter works correctly | | |
| TC_039 | Reports | Verify date filter | Report page open | Select date range | Data filtered | | |
| TC_040 | Reports | Verify report sorting | Report page open | Sort column | Data sorted | | |
| TC_041 | Security | Verify unauthorized access | User logged out | Open dashboard URL | Redirect to login | | |
| TC_042 | Security | Verify password security | Login page open | Enter password | Password secured | | |
| TC_043 | Security | Verify session expiry | User logged in | Stay idle | Session expired | | |
| TC_044 | Security | Verify role access | User roles defined | Login as normal user | Restricted access | | |
| TC_045 | Security | Verify login attempt limit | Login page open | Enter wrong password multiple times | Account locked | | |
| TC_046 | Logout | Verify logout button | User logged in | Click logout | User logged out | | |
| TC_047 | Logout | Verify redirect after logout | User logged out | Access dashboard | Redirect login page | | |
| TC_048 | Logout | Verify session cleared | Logout done | Check session | Session cleared | | |
| TC_049 | Logout | Verify browser back after logout | Logout done | Click browser back | Page not accessible | | |
| TC_050 | Logout | Verify logout confirmation | Logout initiated | Confirm logout | Logout successful | | |
| TC_051 | Performance | Verify login response time | App running | Login with valid user | Response within limit | | |
| TC_052 | Performance | Verify dashboard load time | User logged in | Open dashboard | Dashboard loads quickly | | |
| TC_053 | Performance | Verify multiple users login | System active | Many users login | System stable | | |
| TC_054 | Performance | Verify loan submit response | Loan form filled | Submit form | Process quickly | | |
| TC_055 | Performance | Verify report generation time | Data available | Generate report | Report generated quickly | | |
| TC_056 | Performance | Verify database response | DB connected | Fetch loan data | Data retrieved quickly | | |
| TC_057 | Performance | Verify heavy load performance | System running | Simulate high users | System stable | | |
| TC_058 | Performance | Verify API response time | API active | Send request | Fast response | | |
| TC_059 | Performance | Verify system peak usage | System running | Perform operations | System stable | | |
| TC_060 | Performance | Verify memory usage | System running | Monitor memory | Memory stable | | |
| TC_061 | Validation | Verify mobile validation | Form open | Enter invalid mobile | Error message | | |
| TC_062 | Validation | Verify email validation | Form open | Enter invalid email | Error message | | |
| TC_063 | Validation | Verify mandatory field validation | Form open | Submit empty form | Validation message | | |
| TC_064 | Validation | Verify loan amount validation | Loan form open | Enter negative amount | Error displayed | | |
| TC_065 | Validation | Verify max loan limit | Loan form open | Enter high amount | Validation error | | |
| TC_066 | Validation | Verify minimum loan | Loan form open | Enter small amount | Validation message | | |
| TC_067 | Validation | Verify date validation | Form open | Enter wrong date | Error displayed | | |
| TC_068 | Validation | Verify numeric field validation | Form open | Enter text in number field | Error displayed | | |
| TC_069 | Validation | Verify special characters | Form open | Enter special chars | Error displayed | | |
| TC_070 | Validation | Verify document mandatory | Loan form open | Skip upload | Validation message | | |
| TC_071 | Edge Case | Verify max username length | Login page open | Enter long username | System handles input | | |
| TC_072 | Edge Case | Verify max password length | Login page open | Enter long password | Accepted | | |
| TC_073 | Edge Case | Verify max loan amount | Loan form open | Enter max amount | Loan accepted | | |
| TC_074 | Edge Case | Verify min loan amount | Loan form open | Enter min amount | Loan accepted | | |
| TC_075 | Edge Case | Verify empty search result | Search page open | Search unknown name | No result message | | |
| TC_076 | Edge Case | Verify duplicate customer | Customer form | Enter duplicate data | Error message | | |
| TC_077 | Edge Case | Verify large database records | DB large | Fetch records | System stable | | |
| TC_078 | Edge Case | Verify large file upload | Upload page | Upload large file | Validation applied | | |
| TC_079 | Edge Case | Verify session after timeout | Session expired | Perform action | Redirect login | | |
| TC_080 | Edge Case | Verify page refresh | Form open | Refresh browser | Form reset | | |
| TC_081 | Edge Case | Verify refresh loan form | Loan form open | Refresh page | Data cleared | | |
| TC_082 | Edge Case | Verify network interruption | Operation running | Disconnect network | Error message | | |
| TC_083 | Edge Case | Verify browser compatibility | System running | Open in different browsers | Works correctly | | |
| TC_084 | Edge Case | Verify invalid URL | App running | Enter wrong URL | Error page | | |
| TC_085 | Edge Case | Verify session after logout | Logout done | Open dashboard | Redirect login | | |
| TC_086 | Edge Case | Verify large text input | Form open | Enter long text | Validation works | | |
| TC_087 | Edge Case | Verify special char entry | Form open | Enter symbols | Validation works | | |
| TC_088 | Edge Case | Verify future date entry | Form open | Enter future date | Validation message | | |
| TC_089 | Edge Case | Verify past date entry | Form open | Enter past date | Validation message | | |
| TC_090 | Edge Case | Verify multiple refresh | Dashboard open | Refresh many times | System stable | | |
| TC_091 | Edge Case | Verify multiple tabs | User logged in | Open many tabs | System stable | | |
| TC_092 | Edge Case | Verify logout across tabs | User logged in | Logout one tab | All sessions closed | | |
| TC_093 | Edge Case | Verify loan approved update | Loan approved | Check status | Status updated | | |
| TC_094 | Edge Case | Verify loan rejected update | Loan rejected | Check status | Status updated | | |
| TC_095 | Edge Case | Verify DB restart handling | DB restarted | Access app | System reconnects | | |
| TC_096 | Edge Case | Verify loan deletion | Loan exists | Delete loan | Record removed | | |
| TC_097 | Edge Case | Verify customer update | Customer exists | Update data | Data updated | | |
| TC_098 | Edge Case | Verify maintenance mode | Maintenance active | Access system | Maintenance message | | |
| TC_099 | Edge Case | Verify system backup | Backup scheduled | Run backup | Backup successful | | |
| TC_100 | Edge Case | Verify system restore | Backup available | Restore backup | Data restored | | |
