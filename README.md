# Window Shopper: A MERN store

## Description

Online shopping has become very common these days. People tend to choose online shopping over in-store purchases for a bunch of reasons. 
First, it saves time and energy to physically go to the store and hunt down the very specific thing we are looking for. Second, there is no guarantee whether the item you are looking for actually exists in the store or not. 
Moreover, all stores may or may not be available in your vicinity and in order to buy a specific item you may need to travel a long way to ultimately make the purchase.  

With the boom in eCommerce industry, it has become very convenient to shop online. Users are now used to order their items from the stores of their choice or popular stores that have multiple verified sellers. 

Window Shopper is a typical eCommerce website that helps user fulfil their shopping need. The application not only helps users buy the products of their choice but also provides the opportunity to local sellers to get themselves added to the store as verified sellers. In this way, this app helps local businesses grow and reach out to people on a wider scale.  The application lets its users add items to cart, modify existing orders and cancel the order altogether. It also allows users to browse through the shop items without creating an account.


## Demo

This application's demo can be found at: https://www.youtube.com/watch?v=Jz75ccXS53w

## Step 1: Install

```
$ git clone https://github.com/vatsaashwin/window-shopper.git
$ cd project
$ npm install
```

## Step 2: Setup

```
 Add .env file to include the following:

  PORT=5000
  MONGO_URI=
  JWT_SECRET=
  MAILCHIMP_KEY=
  MAILCHIMP_LIST_KEY=
  MAILGUN_KEY=
  MAILGUN_DOMAIN=
  MAILGUN_EMAIL_SENDER=
  GOOGLE_CLIENT_ID=
  GOOGLE_CLIENT_SECRET=
  GOOGLE_CALLBACK_URL=auth/google/callback
  FACEBOOK_CLIENT_ID=
  FACEBOOK_CLIENT_SECRET=
  FACEBOOK_CALLBACK_URL=auth/facebook/callback
  BASE_CLIENT_URL=http://localhost:5000
  BASE_SERVER_URL=http://localhost:5000
  BASE_API_URL=api
  AWS_ACCESS_KEY_ID=
  AWS_SECRET_ACCESS_KEY=
  AWS_REGION=
  AWS_BUCKET_NAME=

```

## Step 3: Run the application

```
$ npm start
```

## Further developments

- Implement a payment method solution to enable checkout and collecting payments utilising Paypal API and associate Sellers to a payment account
- Enable Admins to manage users module and disable a category, product or a brand
- Enable Sellers to disable their own brand/products/add profucts to a specific category

