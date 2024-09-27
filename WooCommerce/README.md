
# Project Title

A brief description of what this project does and who it's for

NICEPay  WooCommerce - Wordpress Payment Gateway Module
NICEPay  ❤️ WooCommerce! Receive online payment on your WooCommerce store with NICEPay payment gateway integration plugin.

Also Available on Wordpress plugin store

Description
This plugin will allow secure online payment on your WooCommerce store, without your customer ever need to leave your WooCommerce store!

NICEPay-WooCommerce is official plugin from NICEPay. NICEPay is an online payment gateway. We strive to make payments simple & secure for both the merchant and customers. Support various online payment channel. Support WooCommerce v3 & v2.

Please follow this step by step guide for complete configuration. If you have any feedback or request, please do let us know here.

Want to see NICEPay-WooCommerce payment plugins in action? We have some demo web-stores for WooCommerce that you can use to try the payment journey directly, visit the NICEPay CMS Demo Store

how to instal : 

download plugin in https://github.com/nicepay-dev/plugs-libs/tree/master/WooCommerce

go to plugin menu on Wordpress
chose file in your drive and instal plugin
select active plugin

Payment Method Feature:

Credit card, 
Virtual Account,
Payloan,
E-wallet,
Disbursment,
Qris.


Two-click & One-click feature.
NICEPay Snap all supported payment method.
Optional: Separated specific payment buttons with its own icons.
Installation
Minimum Requirements
WordPress v3.9 or greater (tested up to v6.x)
WooCommerce v2 or greater (tested up to v9.1.2)
PHP version v5.4 or greater
MySQL version v5.0 or greater
PHP CURL enabled server/host
Simple Installation
Login to your Wordpress admin panel.
Go to Plugins menu, click add new. Search for NICEPay-WooCommerce plugin.
Install and follow on screen instructions.
Proceed to step 5 below.
Manual Installation
Download the plugin from this repository.
Extract the plugin, then rename the folder modules as NICEPay-woocommerce
Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation's wp-content/plugins/ directory.
Install & Activate the plugin from the Plugins menu within the WordPress admin panel.
Go to menu WooCommerce > Settings > Payment > NICEPay > Manage, fill the configuration fields.
Fill Title with text button that you want to display to customer
Select Environment, Sandbox is for testing transaction, Production is for real transaction
Fill in the client key & server key with your corresonding NICEPay  account credentials
Note: key for Sandbox & Production is different, make sure you use the correct one.
Other configuration are optional, you may leave it as is.
NICEPay  MAP Configuration
Login to your NICEPay  Account, select your environment (sandbox/production), go to menu settings > configuration
Insert http://[your web]/?wc-api=WC_Gateway_NICEPay as your Payment Notification URL.
Insert http://[your web]/?wc-api=WC_Gateway_NICEPay link as Finish/Unfinish/Error Redirect URL.
Go to menu settings > Snap Preference > System Settings
Insert http://[your web]/?wc-api=WC_Gateway_NICEPay link as Finish/Unfinish/Error Redirect URL.
Additional Resource
Note: This section is optional and only for advanced usage.

Configurables
Available for customization from plugin config:

Payment text label of the payment options
Payment text description of the payment options
On both configuration fields above can also input html tags as the text, to insert something like image. For example you can input like this to show images:
Online Payment via Midtrans <img src="https://docs.midtrans.com/asset/image/main/midtrans-logo.png">
You can change the image, like if you want to show the logo of banks or payment providers that you are accepting.

Additional payment options (radio button) can be activated:

Configure it from WooCommerce > Settings > Payment > Nicepay paymethod > Manage under configuration field WC Order Status on Payment Paid. Select your preferred value from the drop down.

Available Custom Hooks
Click to expand info
Customizing Snap API parameters
Click to expand info
Manual Clean Up WP Options Config Value of This Plugin
Click to expand info
Get help
SNAP-Woocommerce Wiki
Veritrans registration
SNAP documentation
Can't find answer you looking for? email to it@nicepay.co.id