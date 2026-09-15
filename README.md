Assignment 2

Node.js Core Modules & CRUD APIs

This assignment implements Node.js core module tasks and a simple CRUD API using a JSON file for data storage.

Part 1: Node.js Core Modules

The assignment covers:

- Working with file and directory paths
- Getting file names and extensions
- Parsing and joining paths
- Checking absolute paths
- Resolving relative paths
- Creating and deleting files/folders
- Event Emitters
- Reading and writing files
- Checking directories
- Getting OS platform and CPU architecture
- Readable and Writable Streams
- Using pipelines and file compression

Part 2: CRUD Operations Using HTTP

All user data is stored in a JSON file using the "fs" module.

Data is not stored or managed using arrays.

APIs

Method| Endpoint| Description
POST| "/user"| Add a new user
PATCH| "/user/:id"| Update an existing user
DELETE| "/user/:id"| Delete a user
GET| "/user"| Get all users
GET| "/user/:id"| Get a user by ID

POST /user

Adds a new user to the JSON file and checks that the email does not already exist.

PATCH /user/:id

Updates the user's name, age, or email by ID and saves the changes to the JSON file.

DELETE /user/:id

Deletes a user by ID from the JSON file.

GET /user

Returns all users stored in the JSON file.

GET /user/:id

Returns a specific user by ID.

Testing

All APIs can be tested using Postman.

The Postman requests should have meaningful names such as:

- Add User
- Update User
- Delete User
- Get All Users
- Get User By ID

Bonus

The bonus solution is implemented in a separate file named:

"bonus.js"

The bonus task is the Kth Missing Positive Number problem from LeetCode.
