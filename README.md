# ReqRes API Testing


This repository demonstrates API testing using Postman on the ReqRes API.


## Features
- CRUD operations: GET, POST, PUT, DELETE
- Functional & Negative testing
- Response code validations (200, 201, 204, 404)
- x-api-key authentication for requests
- Ready-to-run Postman collection


## How to Use
1. Open Postman Web or Desktop
2. Import `ReqRes_API_Testing.postman_collection.json`
3. For POST/PUT/DELETE requests, add the header:
- Key: `x-api-key`
- Value: `reqres-free-v1`
4. Run the requests and check the response and test results.


## Screenshots
- GET User: `screenshots/GET_User.png`
- POST User: `screenshots/POST_User.png`
- PUT User: `screenshots/PUT_User.png`
- DELETE User: `screenshots/DELETE_User.png`


## Notes
- GET requests do not require the API key.
- Negative tests (like GET invalid user `/users/23`) can be added to validate error handling.
