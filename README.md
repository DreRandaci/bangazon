# Bangazon-API
The Bangazon-API provides users with access to information about the Bangazon organization. The company provides information from two domains:
* The **company** itself including Employees, Training Programs and Computer Equipment
* The Bangazon **App** including Customers, Products and Orders

**Access to this API is restricted to employees of Bangazon**

## Installation:

1. Clone or download the repo
1. Configure an environment variable for the database named: ```BANGAZON_API_DB```
1. In the terminal, navigate to the directory with the repo. Begin by installing the required packages.

    ```
    dotnet update
    ```
1. Next, run the command to generate the db
    ```
    dotnet ef database update
    ```
1. Next run the application
    ```
    dotnet run
    ```

# API Resources

## Department
Supports: GET, POST, PUT

### GET
#### Example URL:
/api/
#### Description:
#### Example Response:

## Employee
Supports: GET, POST, PUT

## Training Program
Supports: GET, POST, PUT, DELETE (future start dates only)

## Computer Resources
Supports: GET, POST, PUT, DELETE

## Order
Supports: GET, POST, PUT, DELETE

## Product
Supports: GET, POST, PUT, DELETE

## Customer
Supports: GET, POST, PUT

## Product Category
Supports: GET, POST, PUT, DELETE

## Payment Type
Supports: GET, POST, PUT, DELETE
