# E2E-API-Automation-Tests

Test Plan 

 

**Test Objective:** Ensuring all API endpoints function as expected 

 

Scope of Testing: This plan focuses on API functional testing, including Create, Read, Update, and Delete (CRUD) operations for various endpoints. 

 

**Test Strategy:**

Testing Types: 

Functional Testing: Validating that API endpoints behave as expected. 

End-to-End Testing: Ensuring complete workflows function correctly. 

Performance Testing: Ensuring API can handle the expected load; Checking the response time of requests with large payload and large response data. 

 

**Test tools:** 

Mocha/Chai for automated tests and assertions in JavaScript 

K6: Performance testing 

 

**Test environment:   **

Environment: Staging 

Dependencies: Installed app on the company used for testing, in draft mode with configured webhooks 

All mock data (created resources, users, companies, branches) required for the tests, is deleted after the execution of the tests 

 

**Test Scope and Coverage: **

 

Tested API Endpoints: 

-Get Token 

-Get All Customers 

-Create new customer 

-Get Customer By ID 

-Update Customer 

-Delete customer 

-Retrieve Company Data 

-Retrieve Branch Data 

-Retrieve Service Availability 

-Retrieve Service Avail By External ID 

-Reserve Booking 

-Confirm Booking 

-Delete Booking 

-List all services 

-Create a Service 

-Retrieve a Service 

-Negative Test Retrieve a Service With Wrong service ID 

-Negative Test Create a Service - Missing Body 

-Retrieve Service Booking Limit 

-Reset Service 

-Update a Service 

-Negative Test Update Service with wrong ID 

-Delete a Service 

-List all Service Categories 

-Create Service Category 

-Retrieve Data For Service Category 

-Update Service Category 

-Delete Service Category 

-List all resources 

-Create Resource 

-Update resource 

-Delete a Resource By ID 

-List all appointments 

-Create Appointment 

-Retrieve data for an appointment 

-Update Appointment 

-Delete an appointment 

-List all enterprise customers 

-Create enterprise customer 

-Get enterprise customer 

-Update enterprise customer 

-Delete enterprise customer 

-Get all enterprise custom field categories 

-Create enterprise custom field category 

-GetEnterpriseCustomFieldCategory 

-Update enterprise custom field category 

-Delete enterprise custom field category 

-List all time shifts for a certain resource 

-Create time shift for a resource 

-Get single Time Shift By ID 

-Update a time shift for a resource 

-Delete a time shift for a resource 

-Get information for a company 

-Change online status of a company 

-List all customer custom fields 

-List all custom field categories 

-Retrieve data of a custom field category 

-Create customer custom field category 

-Update custom field category name 

-Delete custom field category 

-List all group services 

-List all group service categories 

-Create group service 

-Update group service 

-Retrieve data for group service by ID 

-Delete a group service 

-Create group service category 

-Update group service category 

-Delete a group service category 


Test Cases: 

Positive test cases: Ensuring the entire flow of the endpoints with valid data is running with correct status code and no errors. 
(Table with described TC, Pre-conditions, Expected and actual result)


Exit Criteria 

Pass Criteria: All API functionalities for the entire flow must pass with no errors. 

Fail Criteria: 1 or more tests fail. 
