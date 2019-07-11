Introduction
=================
**PayPal Here Web SDK is currently in limited release beta**

The PayPal Here SDK enables web based POS apps to process in-person credit card transactions using the [PayPal Chip Card Reader](https://us.paypal-here.com/paypal-chip-card-reader/) which is capable of accepting contactless, EMV, and swipe payment methods.

Developers should use the PayPal Here SDK to get world-class payment processing with one simple integration.  Some of the main benefits include
* **Low, transparent pricing:** US Merchants pay just 2.7% per transaction (or 3.5% + $0.15 for keyed in transactions), including cards like American Express, with no additional hidden/monthly costs.
* **Safety & Security:** PayPal's solution uses encrypted swipers, such that card data is never made available to merchants or anyone else.
* **Live customer support:** Whenever you need support, we’re available to help with our customer support team.
[Visit our website](https://www.paypal.com/webapps/mpp/credit-card-reader) for more information about PayPal Here.
* **Partner program:** Please [contact us](https://www.paypal-business.com/SDKdeveloperinterestregistration) for any partnership program questions or opportunities.


Supporting Materials
========================
 *  This Web SDK is currently in a limited release beta so please contact us through the Partner program link above if you're interested in integrating prior to general availability.


Installation
==============
Similar to any other JS integration, you simply need to include a script tag on your site.  Include the following script as part of your 'Payment' and 'Setup' page to integrate with the PPH Web SDK:
`<script src="https://www.paypalobjects.com/digitalassets/c/pph/content/retailsdk/js/pphwebsdk.min.js"></script>`

All API’s are under the `pphwebsdk` namespace.

Please note that this is the initial link for the limited beta release and, once it's generally available, there will be versioning added to the link that would need to be modified to use the latest version.


Housekeeping Items
=====================
Because this is in limited beta, there are a few limitations that should be called out. These include:
* This SDK is available for the US region only.
* This SDK will only work on desktop/laptop browsers.  Phone/Tablet browsers are not supported yet.
* Only the [PayPal Chip Card Reader](https://us.paypal-here.com/paypal-chip-card-reader/) is supported at this time.
* The only connection method supported for the reader is USB and therefore, the readers are manually pre-configured for this early release.  Because of this, the reader shouldn’t be reset for any reason.
* There is no auth/capture model. Transactions are sale only.
* Vaulting with Braintree is not supported in this early release.


[License](LICENSE.md)
=======
