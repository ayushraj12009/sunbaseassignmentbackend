# SunBase Backend Project
 
## Assignment Project 

This repository contains the codebase for a backend API that manages customer information. The assignment involves implementing various CRUD operations and later extending the functionality in the second phase to synchronize customer data from a remote API.

### Assignment Completion

The following API endpoints have been implemented in the initial phase:
In my case i use http://localhost:8080/home then api end point

1. **Create a Customer**
   - Path: `/api/customers`
   - Method: POST
   - Description: Create a new customer in the system.

2. **Update a Customer**
   - Path: `/api/customers/{customerId}`
   - Method: PUT
   - Description: Update an existing customer's information.

3. **Get a List of Customers**
   - Path: `/api/customers`
   - Method: GET
   - Description: Retrieve a paginated, sorted, and searchable list of customers.

4. **Get a Single Customer Based on ID**
   - Path: `/api/customers/{customerId}`
   - Method: GET
   - Description: Retrieve details of a specific customer based on their ID.

5. **Delete a Customer**
   - Path: `/api/customers/{customerId}`
   - Method: DELETE
   - Description: Delete a customer from the system.
  
6. **Serach a Cutomer by Name, Email, State etc**
   - Path: `/api/customers/search`
   - Method: GET
   - Description: Serach a Cutomer by Name, Email, State, City
  
1st Screen ( **Login Page**)
![image](https://github.com/ayushraj12009/sunbaseassignmentbackend/assets/51042913/a3bc167d-5861-43b7-a8c6-cdd8738e2b6b)

2nd Screen (**Customer Details with edit and delete button**)
![image](https://github.com/ayushraj12009/sunbaseassignmentbackend/assets/51042913/3f526fb6-8af8-4989-a79d-2092f5798e8f)

3rd Screen (**Adding a customer**)
![image](https://github.com/ayushraj12009/sunbaseassignmentbackend/assets/51042913/c83677f6-9d2d-4c5b-9165-fd3f1c592c50)


### Second Phase

In the second phase, additional functionality has been added:

- **Synchronize Customer List**
  - Description: A button named "Sync" has been added on the customer list screen. Clicking this button triggers a call to a remote API to fetch the customer list. The retrieved customers are then saved in the local database. If a customer already exists in the database, their information is updated instead of inserting a new record. for this you need to download frontend repositor or use postman (**for postman**:http://localhost:8080/home/api/customers/search/sunbase)
 
  - **Frontend Code Link**
  - https://github.com/ayushraj12009/sunBaseFrontend.git

### Setup and Usage

1. Clone the repository.
2. Set up the backend environment.
3. Run the backend server.
4. Clone the fronted code.
5. Run the frontend code.
