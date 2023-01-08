# ProShop eCommerce Platform

> eCommerce platform built with the MERN stack & Redux

[Deployed Link](https://champshop.herokuapp.com/)
## Screenshots
Home Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/Screen%20Shot%202020-09-29%20at%205.50.52%20PM.png)

SignUp Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-profile-2023-01-08-23_38_43.png)

Admin OrdersList Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-admin-orderlist-2023-01-08-23_39_43.png)

Admin ProductsList Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-admin-productlist-2023-01-08-23_39_24.png)

Admin UsersList Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-admin-userlist-2023-01-08-23_39_07.png)

Users MyOrders Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-profile-2023-01-08-23_37_03.png)

Users Shopping Cart Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-cart-62bbdfedf691fa52b80b7c78-2023-01-08-23_37_30.png)

Users Product Page
![screenshot](https://github.com/GamerNishant/Proshop-Mern/blob/main/uploads/screencapture-localhost-3000-product-62bbdfedf691fa52b80b7c78-2023-01-08-23_36_26.png)


## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)


## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```
