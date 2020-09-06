=== Pagalo - WooCommerce Payment Gateway ===
Contributors: XicoOfficial, gtcoders, digitallabs
Donate link: https://coders.store.gt/producto/wordpress-plugins/wp-pagalocard-woocommerce/
Tags: pagalo, pagalo guatemala, págalo, págalo guatemala, visanet, visanet guatemala, credomatic, credomatic guatemala, pagalocard, custom gateway, woocommerce payment gateway, pagalo card, woocommerce, págalo card, payment gateway
Requires at least: 3.8
Requires PHP: 5.2.4
Tested up to: 5.5
Stable tag: 1.3.0
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

This plugin allows your store to make payments via PagaloCard service.


== Description ==

= Pagalo - WooCommerce Payment Gateway =

This is a test pluging to check compatibility of your woocommerce store with [Pagalo](https://pagalo.gt/). If the transaction is successful the order status will be changed to “processing”. If the payment charge failed the order status will be changed to “cancelled”. If something is wrong with the connection between your server and the PagaloCard server the order status will be changed to “on-hold”. After successful transaction the customer is redirected to the default WP thank you page.

This is a very basic plugin, feel free to hack it and make it work for your store. There is also an already tested, fully functional and with more features plugin, at [Coders.club.gt](https://coders.store.gt/producto/wordpress-plugins/wp-pagalocard-woocommerce/) that you could purchase to take advantage of the latest features of Pagalo and improve the experience of your customers.

= Support =

Use the wordpress support forum for any questions regarding the plugin, or if you want to improve it.

= Get Involved =

Looking to contribute code to this plugin? Go ahead and [fork the repository over at GitHub](https://github.com/gtcoders/wp-p-pagalo-woocommerce-test).
(submit pull requests to the latest "release-" tag).

== Usage ==

To start using the "Pagalo - WooCommerce Payment Gateway", first create an account at [Pagalo.gt](https://pagalo.gt/). They will provide you with your account "IdenEmpresa", "Token", "Private key" and "Public Key".

After you have your Pagalo account active:

1. Head to Woocommerce Settings and click on the Checkout tab.
2. On checkout options you should see the option "Pagalo", click on it.
3. Enable the payment gateway byt checking the checkbox that reads "Enable this payment gateway".
4. Fill the form with your account information.
5. Click on save changes and you should be ready to start accepting credit cards with Pagalo Card.

Rember that this plugin works only for purchases from Guatemala and in Guatemalan Quetzals. You can use this data to make the testing:
CC Number: 4000-0000-0000-0416 
CVV: 123
Ex date: 08/22

There is also an already tested, fully functional and with more features plugin(support for visacuotas, multiple currencies and countries), at [Coders.club.gt](https://coders.store.gt/producto/wordpress-plugins/wp-pagalocard-woocommerce/) that you could purchase to take advantage of the latest features of Pagalo and improve the experience of your customers.


== Installation ==

Installing "Pagalo Card - WooCommerce Payment Gateway" can be done either by searching for "Pagalo - WooCommerce Payment Gateway" via the "Plugins > Add New" screen in your WordPress dashboard, or by using the following steps:
	
1. Download the plugin via WordPress.org.
1. Upload the ZIP file through the "Plugins > Add New > Upload" screen in your WordPress dashboard.
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= How do I contribute? =

We encourage everyone to contribute their ideas, thoughts and code snippets. This can be done by forking the [repository over at GitHub](https://github.com/gtcoders/wp-p-pagalo-woocommerce-test).

= What key features are missing in this plugin that are already available on the paid version of the plugin? =

The main features that are not included in this free plugin are:
- Support for both modes (Cybersource and ePay).
- Support for Device Fingerprint (a requirement when using Cybersource).
- Support for shipping pricing.
- Support for Offers or dicounts on products.
- Support for a custom Merchant ID, for users with their own Key from Visanet.
- Support for Visa Cuotas and Master Cuotas.
- Support for multiple countries and currencies.
- Support for custom description and title of the payment method.

We encourage you to hack into the code and make it work for your store. If you want to save some time there is also an already tested, fully functional and with more features plugin, at [Coders.store.gt](https://coders.store.gt/producto/wordpress-plugins/wp-pagalocard-woocommerce/) that you could purchase to take advantage of the latest features of Pagalo and improve the experience of your users.


== Screenshots ==

1. The Pagalo payment gateway settings page showing the texts and description that can be customized.

2. The Pagalo payment gateway settings page showing the fields that need to be filled with each individual account information.

3. The checkout page with the Pagalo payment credit card form.

== Changelog ==

= 1.3.0 =
* - Testing copmatibility with WooCommerce 4.4 and WordPress 5.2
* - Update environment url
* - Update description on readme file

= 1.2.2 =
* - Add more detailed notices for both clients and websites admins.

= 1.2.1 =
* - Remove unnecesary messages when payment fails.

= 1.2.0 =
* - Add support for Woocommerce compatibility check.
* - Go back to WP API instead of Curl

= 1.1.1 =
* Go back to using Curl isntead of WP API due to problems with multicurrency(will keep testing and go back to WP API once its fully functional for multi-currency)
* Reorder the post fields on wordpress settings page to match the orther they are displayed on the PagaloCard platform.

= 1.1.0 =
* Add banner and icon images
* Add readme.txt file

= 1.0.0 =
* Integration with PagaloCard to acept credit card payments. 


== Upgrade Notice ==
= 1.2.0 =
* Added support for Woocommerce 4.1.

= 1.2.0 =
* Add support for Woocommerce compatibility check.

= 1.1.0 =
* Get the plugin ready to upload to the WordPress repo

= 1.0.0 =
* Initial release. Yeah!

