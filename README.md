# Vault Python demo using Flask 

This is a reall basic example of the Braintree Vault in Python using Flask to create a customer and attach a payment method, being stored in the Braintree Vault. Once stored a token is returned that can be stored and transacted against as needed.

## Technology

This demo uses

* Python 2.7+
* The [flask](http://flask.pocoo.org/) web framework

## Demo

* Fill in the following credentials:
  * Number: `4111 1111 1111 1111`
  * CVV: `123`
  * Expiration date: `11/2020`
* Click submit

or you can sign in using your PayPal Sandbox account

## Running the demo locally

* Run `pip install flask` to install flask
* Run `pip install braintree` to install braintree 
* Run `Python app.py` in the root project folder to run the server 
* Visit `http://127.0.0.1:5000/` in your browser
* Proceed as above
