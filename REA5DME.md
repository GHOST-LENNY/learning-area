# A RESTful CRUD API built with Node, MongoDB, and Express.


## ❯ Getting Started

### Step 1: Set up your Development Environment

Install Node.js in your computer.


### Step 2: Create your new Project

Clone or download this project into your own project 



Then setup your application environment.


### Install

- Install all dependencies with `npm install` command


## ❯ Postman
You can use Postman for testing the API. 
Create a new post request to http://localhost:7777/api with this in the body. You can also you your hosting site url.
{
"name": "Satoru Gojo"
}
POST /api
## ❯ POST Request Response
{
"newPerson": {
"_id": "6502152763bcef1970ba0a28",
"name": "Satoru Goju",
"__v": 0
}
}

## GET request
GET /api/:user_id
## ❯ GET Request Response
{
"person": {
"_id": "6502152763bcef1970ba0a28",
"name": "Satoru Gojo",
"__v": 0
}
}

## PUT request
PUT /api/:user_id
## ❯ PUT Request Response
{
"updatedPerson": {
"_id": "64ff1ea91539022f0c4d1d98",
"name": "Satoru Goj",
track: "Backend"
"__v": 0
}
}

## DELETE request
Select DELETE on PostMan
DELETE /api/:user_id
## ❯ DE
LETE Request Response
{
"message": "Person deleted successfully"
}
