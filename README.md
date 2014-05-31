UserApp + Stripe
================

Demonstration of how to use [UserApp](https://www.userapp.io/) and [Stripe](https://stripe.com/) to create pricing with sign-up.

## Getting Started

**Sign up for UserApp and Stripe**

For this demo you'll need a [UserApp account](https://app.userapp.io/#/sign-up/) and a [Stripe account](https://manage.stripe.com/register).

**Configuration**

Open the file `js/config.js` and replace the following parameters:

* `YOUR_APP_ID` - Replace with your App Id: <http://help.userapp.io/customer/portal/articles/1322336-how-do-i-find-my-app-id->
* `YOUR_TOKEN` - Replace with an API token with permissions set to `plan.search, plan.get`: <http://help.userapp.io/customer/portal/articles/1364103-how-do-i-create-an-api-token->
* `PRICE_LIST_ID` - Set up a price list with different plans and replace this with your price lsit id: <http://help.userapp.io/customer/portal/articles/1245685-setting-up-your-price-lists>
* `YOUR_PUBLISHABLE_STRIPE_KEY` - Replace with your Publishable Key from Stripe

**Test it**

Open the file `pricing.html` in your browser. If it works, it should display your price plans that you previously set up. Else it will display an error message with further instructions.

Click on "Sign Up" on one of the plans. This should take you to `signup.html` where you can enter your information and a credit card. It will also display more detailed plan costs.

Once the form has been filled in and submitted, the stated amount will be charged from the credit card and the user will be signed up with the selected subscription. A message will be shown with a login button.

## Help

Contact us via email at support@userapp.io or visit our [support center](https://help.userapp.io). You can also see the [UserApp documentation](https://app.userapp.io/#/docs/) for more information.

## License

MIT, see LICENSE.
