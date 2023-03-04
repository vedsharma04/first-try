# commerce-services-api
API's for commerce services built on NodeJs 

===
## Overview
The server is built on nodeJS with expressJS framework, all the APIs can be accessed via swagger UI

===
## Running the server

`npm run dev`
Runs the server in developement mode using nodemon.

===
## Accessing the Swagger UI (API Documentation)

Swagger Ui can be accessed in local by --> (http://localhost:9050/api/docs)

===
## List of APIs

The server supports following APIs

### Register
POST `/api/auth/register`

### Login
POST `/api/auth/login`

## APIs for buyers

### List of Sellers
GET `/api/buyer/list-of-sellers`

### Seller Catalog
GET `/api/buyer/seller-catalog/:seller_id`

### Create Order
POST `/api/buyer/create-order/:seller_id`

## APIs for sellers

### Create Catalog
POST `/api/seller/create-catalog`

### Orders
GET `/api/seller/orders`

===
