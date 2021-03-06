## Description

A Stripe Node.js Boilerplate

![App Screenshot](public/img/screenshot.png)

## Prerequisites
[Node.js (v9)](https://nodejs.org/en/)

[Stripe Account](https://dashboard.stripe.com/register)

## Instructions

Follow the steps below to get the app running on your local machine.

First, clone the repository and install dependencies.
```bash
$ git clone https://git.corp.stripe.com/stripe-internal/sales-node-demo-boilerplate.git
$ cd stripe-node-boilerplate
$ npm install
```

Fetch your Stripe Publishable/Secret keys from the [Stripe Dashboard](https://dashboard.stripe.com/account/apikeys) and add them to your local .env file (rename sample.env to .env).

Start the server.

```bash
$ npm start
```

Open a web browser and navigate to [http://localhost:3000/](http://127.0.0.1:3000/)
to see the example in action.
