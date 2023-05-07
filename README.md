# Ecomerce-Node-Js-Api

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Available Scripts](#Available-Scripts)


## General info
This project is an E commerce Node JS Api with all functionality like Model CRUD operation , filtration, search, sort, pagination, localization, authorization , authentication , send Email and more. 


## Technologies
Project is created with:
* Node js
* Express
* mongodb
* i18n
* nodemailer

## Setup
To run this project you must install node.js and npm  on your machine , and add these environment variables :
PORT
ENVIRONMENT
SECRET
DB_URI 
USER_EMAIL
EMAIL_PASSWORD
EMAIL_IMG 
then requires only `npm install` and `npm start` to get it installed and launched.



## Available Scripts

In the project directory, you can run:

npm start to run project

npm run start-dev to run project with nodemon



## Documentation
### Endpoints
#### Products
##### Get: https://lazy-jade-goat-wear.cyclic.app/products (get all products)
##### Get: https://lazy-jade-goat-wear.cyclic.app/products/:id (get one product)
##### Post: https://lazy-jade-goat-wear.cyclic.app/products (create product only admin can create product)
##### Put: https://lazy-jade-goat-wear.cyclic.app/products/:id (update product only admin can update product)
##### delete: https://lazy-jade-goat-wear.cyclic.app/products/:id (delete product only admin can delete product)

#### categories
##### Get: https://lazy-jade-goat-wear.cyclic.app/categories (get all categories)
##### Get: https://lazy-jade-goat-wear.cyclic.app/categories/:id (get one category)
##### Post: https://lazy-jade-goat-wear.cyclic.app/categories (create category only admin can create category)
##### Put: https://lazy-jade-goat-wear.cyclic.app/categories/:id (update category only admin can update category)
##### delete: https://lazy-jade-goat-wear.cyclic.app/categories/:id (delete category only admin can delete category)

#### sub-categories
##### Get: https://lazy-jade-goat-wear.cyclic.app/subCategories (get all subCategories)
##### Get: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (get one subCategory)
##### Post: https://lazy-jade-goat-wear.cyclic.app/subCategories (create subCategory only admin can create subCategory)
##### Put: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (update subCategory only admin can update subCategory)
##### delete: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (delete subCategory only admin can delete subCategory)

#### Users
##### get: https://lazy-jade-goat-wear.cyclic.app/users/user_data
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/register
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/verify_email
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/login
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/forgot_password
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/verify_reset_code
##### Post: https://lazy-jade-goat-wear.cyclic.app/users/reset_password
##### Put: https://lazy-jade-goat-wear.cyclic.app/users/update_profile
##### Put: https://lazy-jade-goat-wear.cyclic.app/users/change_password
##### delete: https://lazy-jade-goat-wear.cyclic.app/users/deactivate_user

#### reviews
##### Get: https://lazy-jade-goat-wear.cyclic.app/reviews (get all reviews)
##### Get: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (get one review)
##### Post: https://lazy-jade-goat-wear.cyclic.app/reviews (create review)
##### Put: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (update review)
##### delete: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (delete review)


#### orders
##### Get: https://lazy-jade-goat-wear.cyclic.app/orders (get all orders)
##### Get: https://lazy-jade-goat-wear.cyclic.app/orders/:id (get one order)
##### Post: https://lazy-jade-goat-wear.cyclic.app/orders (create order)
##### Put: https://lazy-jade-goat-wear.cyclic.app/orders/:id (update order)
##### delete: https://lazy-jade-goat-wear.cyclic.app/orders/:id (delete order)

#### cart
##### Get: https://lazy-jade-goat-wear.cyclic.app/carts (get User Cart)
##### Post: https://lazy-jade-goat-wear.cyclic.app/carts (add Product To Cart)
##### delete: https://lazy-jade-goat-wear.cyclic.app/carts (clear Cart)
##### Put: https://lazy-jade-goat-wear.cyclic.app/carts/:id (update Cart Item Quantity)
##### delete: https://lazy-jade-goat-wear.cyclic.app/carts/:id (remove Cart Item)
