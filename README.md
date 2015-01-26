Magento-ChainPay
================

A Magento module to enable payment with cryptocurrency via ChainPay's payment gateway.


Installation Instructions:
====================

* Ensure you have Magento version 1.9.1.0 or higher.
* Copy the 'app' folder contained in this repository to the root directory of your Magento installation.
* Once installed, you must activate the ChainPay Payment Method using the Magento Admin Panel.
* In the Magento Admin Panel go to System > Configuration > Payment Methods
* You will need to provide an API Key from the [ChainPay portal](https://portal.chainpay.com) Settings page, and also your Private Key.
* Once these details have been provided, you can Select 'Enabled' and customers will be able to select Bitcoin as a payment option.
* Put through a test order to ensure ChainPay notifications change the Payment status to 'Processing' when a payment occurs.
* If there are any issues email ChainPay support at questions@chainpay.com


License:
====================

ChainPay Magento module is released under the MIT license.

The MIT License

Copyright (c) 2014 < AltXE Limited >

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
