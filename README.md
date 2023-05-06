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
Products
Get: https://lazy-jade-goat-wear.cyclic.app/products (get all products)
Get: https://lazy-jade-goat-wear.cyclic.app/products/:id (get one product)
Post: https://lazy-jade-goat-wear.cyclic.app/products (create product only admin can create product)
Put: https://lazy-jade-goat-wear.cyclic.app/products/:id (update product only admin can update product)
delete: https://lazy-jade-goat-wear.cyclic.app/products/:id (delete product only admin can delete product)

categories
Get: https://lazy-jade-goat-wear.cyclic.app/categories (get all categories)
Get: https://lazy-jade-goat-wear.cyclic.app/categories/:id (get one category)
Post: https://lazy-jade-goat-wear.cyclic.app/categories (create category only admin can create category)
Put: https://lazy-jade-goat-wear.cyclic.app/categories/:id (update category only admin can update category)
delete: https://lazy-jade-goat-wear.cyclic.app/categories/:id (delete category only admin can delete category)

sub-categories
Get: https://lazy-jade-goat-wear.cyclic.app/subCategories (get all subCategories)
Get: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (get one subCategory)
Post: https://lazy-jade-goat-wear.cyclic.app/subCategories (create subCategory only admin can create subCategory)
Put: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (update subCategory only admin can update subCategory)
delete: https://lazy-jade-goat-wear.cyclic.app/subCategories/:id (delete subCategory only admin can delete subCategory)

reviews
Get: https://lazy-jade-goat-wear.cyclic.app/reviews (get all reviews)
Get: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (get one review)
Post: https://lazy-jade-goat-wear.cyclic.app/reviews (create subCategory only admin can create subCategory)
Put: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (update subCategory only admin can update subCategory)
delete: https://lazy-jade-goat-wear.cyclic.app/reviews/:id (delete subCategory only admin can delete subCategory)
