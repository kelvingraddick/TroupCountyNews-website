# Troup County News website

[Website](http://troupcountynews.wavelinkllc.com) to sign up for **Troup County News** subscriptions. Great example of  using client-side [Stripe Checkout for subscriptions](https://stripe.com/docs/payments/checkout/client-subscription).

Coded with ❤️ by [KG.codes](https://www.kg.codes).


## Installation

1. Update the assets/**configuration.js** file with the Stripe configuration values:

```bash
stripeConfiguration.API_KEY: 'Stripe API Key'
stripeConfiguration.PRODUCT_1_ID: 'Stripe product 1 ID'
stripeConfiguration.PRODUCT_2_ID: 'Stripe product 2 ID'
stripeConfiguration.PRODUCT_3_ID: 'Stripe product 3 ID'
stripeConfiguration.PRODUCT_4_ID: 'Stripe product 4 ID'
```

2. Simply upload all the files to a web hosting server.

## Usage

Hit the 'Subscribe' button on a plan; you will be redirected to a Stripe Checkout page.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)