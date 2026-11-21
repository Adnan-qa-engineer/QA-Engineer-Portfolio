Practical API Testing Project

1. Project Overview

This project demonstrates practical API testing using Postman. The objective is to validate API requests, responses, status codes, and response data.

2. Testing Tool

- Tool: Postman
- API Type: REST API
- Data Format: JSON
- Request Methods: GET, POST, PUT, DELETE

3. API Under Test

Public Testing API: JSONPlaceholder

Base URL:
https://jsonplaceholder.typicode.com

4. Test Scenarios

Test Case ID| Request| Expected Status Code| Expected Result
API_001| GET /posts/1| 200| Post details returned
API_002| GET /users/1| 200| User details returned
API_003| GET /comments/1| 200| Comment details returned
API_004| POST /posts| 201| New post created
API_005| GET /invalid| 404| Resource not found

5. Validation Checklist

- Verify HTTP status code.
- Verify response body.
- Verify JSON format.
- Verify required response fields.
- Verify response time.
- Verify error handling.

6. Test Execution Results

Test execution results will be updated after running the API requests in Postman.

7. Conclusion

This project demonstrates the fundamentals of practical API testing, including HTTP methods, response validation, status code verification, and negative testing.

Project Status: Test Execution Pending
