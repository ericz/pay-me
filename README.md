# Let's pay me!


[Stripe API Reference](https://stripe.com/docs/api)

[Stripe.js Frontend](https://stripe.com/docs/stripe.js)


### Stripe Live
Secret key: `sk_0A8xJz54EqeefDQAl6n1ZqUT82VwX`
Public key: `pk_0A8xerxuWrYLPjvPHU4E6QDiHQcag`
  
  
  
![100% Secure](http://i.imgur.com/yli2YMN.jpgg)

## 1. Take your credit card
Our first step is to create a credit card form in HTML.

For an example solution see `form.html`

## 2. ???
Here's the fun part: now we use the Stripe API to actually charge your credit card. Turns out this whole time the `???` step was really just using an API!

We'll be using a GUI HTTP client called Postman for Chrome: 

[Download Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)

**API Routes:**  
`POST https://api.stripe.com/v1/charges`

## 3. Profit!

Great. To ensure that I have captured your money, we're going to use the Strip API again to check that the we've correctly captured your dollar.

**API Routes:**  
`GET https://api.stripe.com/v1/charges`  
`GET https://api.stripe.com/v1/charges/{CHARGE_ID}`

