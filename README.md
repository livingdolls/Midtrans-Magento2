
Midtrans&nbsp; Magento Payment Gateway Module
=====================================

Midtrans&nbsp; :heart:Magento!

### Description

Midtrans payment gateway is an online payment gateway that is highly concerned with customer experience (UX). They strive to make payments simple for both the merchant and customers. With this plugin you can make your Magento store using Midtrans payment.

Payment Method Feature:

* Credit card fullpayment and other payment methods.
* Bank transfer, internet banking for various banks
* Credit card Online & offline installment payment.
* Credit card BIN, bank transfer, and other channel payment.
* Custom expiry.
* Two-click & One-click feature.
* Midtrans Snap all payment method fullpayment.

### Installation

#### Minimum Requirements

* This plugin is tested with Magento version 2.3.x
> ###### Note : if you are using Magento 2 version less than 2.3.x (2.0.x, 2.1.x, 2.2.x) and notification doesn't seem to work, please try this version: [magento2-pre-version-2.3](https://github.com/Midtrans/SNAP-Magento2/tree/magento2-pre-version-2.3)

#### Simple Installation
1. Download and extract the zip.
2. Locate the root Magento directory of your shop via FTP connection.
3. Copy the 'app' & 'lib' folders into magento root folder.
4. Login to your Magento Admin Panel.
5. Go to `System` - `Web Setup Wizard` - `Module Manager`.
6. Scroll or go to the next page untill you find **Midtrans_Snap**.
7. Click `Select` - `Enable` to enable the module.
8. Proceed to step **5** below.

#### Manual Instalation

1. Download and extract the zip.
2. Locate the root Magento directory of your shop via FTP connection
3. Copy the 'app' & 'lib' folders into magento root folder
4. Run below command:
```
php bin/magento module:enable --clear-static-content Midtrans_Snap
php bin/magento setup:upgrade
php bin/magento cache:clean
```
5. Login to your Magento Admin Panel.
6. In your Magento admin area, enable the Midtrans plug-in and insert your merchant details (Server key and client key) in the Menu "Stores" > "Configuration" > "Sales" > "Payment Method" > Tab "Midtrans Snap".

### Midtrans&nbsp;  MAP Configuration
1. Login to your [Midtrans&nbsp;  Account](https://dashboard.midtrans.com), select your environment (sandbox/production), go to menu `settings > configuration`
   * Payment Notification URL: 
    >`http://[your-site-url]/snap/payment/notification`
   * Finish Redirect URL: 
    >`http://[your-site-url]/snap/index/finish`
   * Unfinish Redirect URL: 
    >`http://[your-site-url]/snap/index/finish`
   * Error Redirect URL: 
    >`http://[your-site-url]/snap/index/finish`


#### Get help

* [General Documentation Midtrans](http://docs.midtrans.com)
* Technical Support Team Midtrans [support@midtrans.com](mailto:support@midtrans.com)
* [SNAP Documentation Product Midtrans](https://snap-docs.midtrans.com/)
* [CoreAPI Documentation Product Midtrans](https://api-docs.midtrans.com/)
* [Mobile Documentation Product Midtrans](http://mobile-docs.midtrans.com/)
