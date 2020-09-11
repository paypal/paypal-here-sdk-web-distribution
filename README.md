Introduction
=================

The PayPal Here SDK enables web based POS apps to process in-person credit card transactions using the [PayPal Chip Card Reader](https://us.paypal-here.com/paypal-chip-card-reader/) which is capable of accepting contactless, EMV, and swipe payment methods.

Developers should use the PayPal Here SDK to get world-class payment processing with one simple integration.  Some of the main benefits include
* **Low, transparent pricing:** US Merchants pay just 2.7% per transaction (or 3.5% + $0.15 for keyed in transactions), including cards like American Express, with no additional hidden/monthly costs.
* **Safety & Security:** PayPal's solution uses encrypted swipers, such that card data is never made available to merchants or anyone else.
* **Live customer support:** Whenever you need support, we’re available to help with our customer support team.
[Visit our website](https://www.paypal.com/webapps/mpp/credit-card-reader) for more information about PayPal Here.
* **Partner program:** Please [contact us](https://www.paypal-business.com/SDKdeveloperinterestregistration) for any partnership program questions or opportunities.


Supporting Materials
========================
 *  PPH SDK documentation can be found [here](https://developer.paypal.com/docs/integration/paypal-here/).


Installation
==============
As with our iOS/Android SDKs, there are debug and release versions of the SDK. The debug version contains extra logging and should only be used for development. You will utilize the release version once you're ready for your site to be live. Similar to any other JS integration, you simply need to include a script tag on your site. Include the following script as part of your 'Payment' and 'Setup' page to integrate with the PPH Web SDK:

Release: `<script src="https://www.paypalobjects.com/pph/websdk/js/pphwebsdk-1.1.12.min.js"></script>`

Debug: `<script src="https://www.paypalobjects.com/pph/websdk/js/pphwebsdk-1.1.12-debug.min.js"></script>`

All APIs are under the `pphwebsdk` namespace.

Once the mediator app is installed, it will create a log file on the computer in the following default location:

`C:/Users/<username>/.pphweb/logs/app.log`

This log file will be useful in troubleshooting any integration issues and/or any error situations that may occur.


Housekeeping Items
=====================
There are a few noteworthy items that should be called out. These include:
* This SDK is available for the US region only.
* This SDK will only work on Windows 10 desktop/laptop browsers.  Phone/Tablet browsers are not supported.
* The latest versions of Firefox and Chrome are supported but if you use IE then please note only IE 11 is supported.
* The card readers that are supported with this SDK are the [Chip Card Reader](https://www.paypal.com/us/webapps/mpp/credit-card-reader-how-to/chip-card-reader), the [Chip and Tap Reader](https://www.paypal.com/us/webapps/mpp/credit-card-reader-how-to/chip-and-tap-reader), and the Verifone P400 reader. You can order the Chip Card Reader from our [web store](https://us.paypal-here.com/card-readers/) as normal but the Chip and Tap readers and P400 readers need manual configuration to allow the USB connection. Therefore, if you would like to order Chip and Tap readers or Verifone P400 readers, please send an email to [pph-inquiry@paypal.com](mailto:pph-inquiry@paypal.com).


[License](LICENSE.md)
=======
