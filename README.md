# Node.js and Express CRUD API

This is a RESTful API built using Node.js and the Express web framework. It allows users to perform CRUD (Create, Read, Update, and Delete) operations on data stored in a JavaScript array.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

* Node.js
* npm

### Installation

1. Clone the repository to your local machine

```bash
  git clone https://github.com/MunemHashmi/nodejs-express-crud-api.git
```
2. Install dependencies

```bash
  cd nodejs-express-crud-api
  npm install
```

### Running the server

```bash
  npm start
```

## API Endpoints

### GET /users

Returns a list of all users in the JavaScript array.

### POST /users

Creates a new user in the JavaScript array.

### GET /users/:id

Returns the details of a specific user by their ID.

### DELETE /users/:id

Deletes a specific user from the JavaScript array by their ID.

### PATCH /users/:id

Updates the details of a specific user by their ID.

## Built With

* Node.js
* Express
