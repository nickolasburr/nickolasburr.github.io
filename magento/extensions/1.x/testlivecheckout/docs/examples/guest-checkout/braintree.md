# Braintree Guest Checkout

<blockquote class="important">This documentation is for Magento 1.x. For Magento 2.x, see <a href="https://docs.auroraextensions.com/magento/extensions/2.x/testlivecheckout/latest/">here</a>.</blockquote>
<blockquote class="important"><a href="https://marketplace.magento.com/paypal-gene-braintree.html" target="_blank">Braintree Payments With Hosted Fields</a> is required by Test Live Checkout to use Braintree.</blockquote>
<blockquote class="notice">Tests were performed using Puppeteer, Magento 1.9.3.9 CE with sample data, and Braintree.</blockquote>

## Download

You can download <tt>braintree.js</tt> [here](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/src/guest-checkout/braintree.js).

## Purpose

To simulate a guest checkout scenario on a Magento 1.x storefront using Braintree.

## Steps

1. Visit Home page and click on <tt>Bed & Bath</tt> link under __Home & Decor__ navigation menu
2. On __Bed & Bath__ category page, click <tt>Add to Cart</tt> button on first product
3. On __Cart__ overview page, click <tt>Proceed to Checkout</tt>
4. On __Checkout__ page, click <tt>Checkout as Guest</tt>
5. Fill in __Billing Information__ section and click <tt>Continue</tt>
6. Select <tt>Flat Rate</tt> option as shipping method and click <tt>Continue</tt>
7. Fill in __Payment Information__ section and click <tt>Continue</tt>
8. Click <tt>Place Order</tt> to submit order
9. On success, redirect to Home page

## Walkthrough

![Braintree Guest Checkout -- Walkthrough](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/walkthrough.gif)

## Screenshots

![Braintree Guest Checkout -- Step 1](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-01.png)
![Braintree Guest Checkout -- Step 2](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-02.png)
![Braintree Guest Checkout -- Step 3](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-03.png)
![Braintree Guest Checkout -- Step 4](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-04.png)
![Braintree Guest Checkout -- Step 5](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-05.png)
![Braintree Guest Checkout -- Step 6](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-06.png)
![Braintree Guest Checkout -- Step 7](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-07.png)
![Braintree Guest Checkout -- Step 8](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-08.png)
![Braintree Guest Checkout -- Step 9](https://docs.auroraextensions.com/magento/extensions/1.x/testlivecheckout/1.1.0/puppeteer/img/guest-checkout/braintree/step-09.png)
