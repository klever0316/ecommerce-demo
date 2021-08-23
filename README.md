
![Gem logo](https://raw.githubusercontent.com/klever0316/ecommerce-demo/656cf03aebf344741fbed4e9dd27768a93beb4b3/public/readme_images/logo.svg)
 
## Solidus Gem Demo (E-Commerce app)
 
A free, open-source ecommerce platform that gives you complete control over your store.

* Git: https://github.com/solidusio/solidus
* Website: https://solidus.io/

## Tecnologies
 
* Ruby 2.5.0
* Rails 5.1.4
* PostgreSQL
* Gem Solidus
 
## Services
 
* GIT
* Docker + Docker-Compose
* Cloudinary
* Heroku / Heroku Cli
 
## Getting Started with Docker (Local)
 
* Build project and start Dockerfile:
>    $ docker-compose build
* Create database:
>    $ docker-compose run web rake db:create
* Migrate database:
>    $ docker-compose run web rails db:migrate
* Fill database:
>    $ docker-compose run web rake db:seed
* Provide admin and password data (e.g., admin@test.com) (e.g., test123)
* Reload images files:
>    $ docker-compose run web rake assets:precompile
* Load sample app data:
>    $ docker-compose run web rake spree_sample:load
* Start system on localhost 3000:
>    $ docker-compose up

## Deployed App (Heroku)

* User access:

https://ecommerce-solidus-demo.herokuapp.com/

* Admin access:

https://ecommerce-solidus-demo.herokuapp.com/admin

## How to Use
 
## 1 - Home - You can see the products and their prices on the store, filter and search by product type, get access to you account, create a new one or logout, see items on the cart and choose which order you will made
![Home](https://raw.githubusercontent.com/klever0316/ecommerce-demo/master/public/readme_images/home.png)

## 2 - Product Detail - You can check the product details, image, size, price, color, properties, similar items and you can choose how many items do you want to add to the cart
![Product Detail](https://raw.githubusercontent.com/klever0316/ecommerce-demo/master/public/readme_images/product-detail.png)

## 3 - Shopping Cart - You can see the products that you add to the cart, remove or add more items or of the same product to update the cart, see the total, checkout, add coupoun code, empty cart ou just keep shopping
![Shopping Cart](https://raw.githubusercontent.com/klever0316/ecommerce-demo/master/public/readme_images/shopping-cart.png)

## 4 - Checkout Page - You can process your order, filling the fields with your information, see the total order, procced to delivery, payment, confirm and complete page, passing through all the steps to buy a product
![Checkout Page](https://raw.githubusercontent.com/klever0316/ecommerce-demo/master/public/readme_images/checkout-page.png)

## 5 - Admin Page - You can manage the orders, products, promotions, stock, users and get access to functions that allowed you control the app, users and orders, approve shipping, create promotion, discounts, track records, stock control and many others
![Admin Page](https://raw.githubusercontent.com/klever0316/ecommerce-demo/master/public/readme_images/admin-page.png)

## App Info
 
With the app you can have:
  - An E-Commerce app ready to use with an admin page
  - Connection with Paypal to checkout orders
  - Add items to the cart (one or more), checkout and get delivery (adjustable on admin page)
  - Adjust prices, made discounts, choose how you will charged for the shipping...
