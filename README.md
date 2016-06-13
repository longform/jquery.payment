# jQuery.payment [![Build Status](https://travis-ci.org/stripe/jquery.payment.svg?branch=master)](https://travis-ci.org/stripe/jquery.payment)

A general purpose library for building credit card forms, validating inputs and formatting numbers.

## Fork Information

This fork removes the spaces in the expiration date formatter, so that the field
is formatted and validated as "MM/YY" rather than "MM / YY". This makes it compatible
with Braintree, a competitor to Stripe. Sorry, Stripe, but we need that Paypal
button.

## Original Documentation

For all other documentation, see the [upstream repository](https://github.com/stripe/jquery.payment)