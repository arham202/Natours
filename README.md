<h1 align="center">
  <br>
  <a href="https://natours-xbsh.onrender.com/"><img src="https://github.com/ritiksharmarj/natours/assets/54701022/326dd79a-8751-4d1d-883f-b302cf0461c5" alt="Natours" width="200"></a>
  <br>
  Natours
  <br>
</h1>

<h4 align="center">An awesome tour booking site built on top of <a href="https://nodejs.org/en/" target="_blank">NodeJS</a>.</h4>
 <p align="center">
 <a href="#deployed-version">Demo</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#update-your-profile">Update your profile</a> •
  <a href="#api-usage">API Usage</a> •
  <a href="#installation">Installation</a> • 
</p>

## Deployed Version

Live demo 👉 : https://natours-92pt.onrender.com/

## Key Features

- Authentication and Authorization
  - Signup, Login and logout
- Tour
  - Manage booking, check tours map, check user's reviews and ratings
- User profile
  - Update username, profile photo, email, and password
- Credit card payment using Stripe

## Demonstration

<img src='https://github.com/arham202/Natours/blob/66d1cfc56e35008f9fe374bba667e5a7687871d3/1.png'>

## How To Use

### Book a tour

- Login or Signup to the site
- Search for tours that you want to book
- Book a tour
- Proceed to the payment using Stripe
- Enter the card details (Test Mode):
  ```
  - Card No. : 4242 4242 4242 4242
  - Expiry date: any
  - CVV: any
  ```
- Finished!

### Manage your booking

- Check the tour you have booked in "Manage Booking" page in your user settings. You'll be automatically redirected to this
  page after you have completed the booking.

### Update your profile

- You can update your own username, profile photo, email and password.

## API Usage

Before using the API, you need to set the variables in Postman depending on your environment (development or production). Simply add:

```
- {{URL}} with your hostname as value (e.g. http://127.0.0.1:8000 or http://www.example.com)
- {{password}} with your user password as value.
```

<b> API Features: </b>

- Tours List

- Tours Statistics

- Get Top 5 Cheap Tours

- Get Tours Within Radius

## Build With

- [NodeJS](https://nodejs.org/en/) - JS runtime environment
- [Express](http://expressjs.com/) - The web framework used
- [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
- [Pug](https://pugjs.org/api/getting-started.html) - High performance template engine
- [JSON Web Token](https://jwt.io/) - Security token
- [esbuild](https://esbuild.github.io/) - An extremely fast bundler for the web
- [Stripe](https://stripe.com/) - Online payment API
- [Postman](https://www.getpostman.com/) - API testing
- [Mailtrap](https://mailtrap.io/) & [Mailgun](https://www.mailgun.com/) - Email delivery platform
- [Render](https://render.com/) - Cloud platform

## Installation

You can fork the app or you can git-clone the app into your local machine. Once done that, please install all the
dependencies by running

```
$ npm i
set your env variables
$ npm run watch
$ npm run dev (for development)
$ npm run prod (for production)
$ npm run debug (for debug)
```
