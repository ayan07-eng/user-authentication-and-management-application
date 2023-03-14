# user-authentication-and-management-application

This API provides user authentication and management functionality. It is built using Express.js and bcrypt.

## Installation
To install this API, you will need Node.js installed on your system. You can install the dependencies by running the following command in the project directory:

```bash
npm install
```


## Usage
To start the server, run the following command in the project directory:
node server.js

The server will start on http://localhost:3000/.

## Endpoints
This API provides the following endpoints:

**`GET /users:`** Returns a list of all users in the system.

**`POST /users:`** 
Creates a new user with the given name and password. The      password is hashed using bcrypt before being stored in the database.

**`POST /users/login:`** 
     Logs in a user with the given name and password. The API checks if the user exists and if the password is correct. If the user is authenticated, the API returns a message indicating success; otherwise, it returns a message indicating failure.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## Credits
This API was created by Ayan.
