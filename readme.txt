=== wePOS - Point Of Sale (POS) for WooCommerce ===
Contributors: tareq1988, wedevs, sabbir1991, nizamuddinbabu
Donate Link: http://tareq.co/donate/
Tags: WooCommerce POS, point of sale, free pos, pos plugin, woocommerce point of sale
Requires at least: 4.4
Tested up to: 5.1.1
WC requires at least: 3.0
WC tested up to: 3.5.7
Requires PHP: 5.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WooCommerce point of sale WordPress plugin.

== Description ==

= WooCommerce Point of Sales (POS) =
wePOS is a fast and responsive( Tablets & Desktop ) WooCommerce Point of Sales plugin. It lets you take orders and track your inventory using your WooCommerce store. You can physically count your WooCommerce products by scanning Bar codes and add them directly to customer’s cart for processing the order.

= Based of REST API =
wePOS is a single page application that works super fast. We have used WooCommerce REST API and some custom API to develop the plugin. This has made the plugin to response fast and gets your work done in time. In a physical store, you get a lot of customers who wait to checkout their products. So, a fast system like wePoS can be your one-way ticket to manage your inventory easily.

= Attractive User Interface =
A good UI can sometimes makes a system even more attractive. wePOS has an intuitive design that allows navigating easily. With it, you can manage your inventory and orders in an organized way.

= Shortcut / Hotkey Support =
wePOS has shortcut key support that lets you use its features faster. This is very important for any physical store so that the sales executive can read the Barcodes and process the orders with pace.

= Contribute =
This may have bugs and lack of many features. If you want to contribute on this project, you are more than welcome. Please fork the repository from [Github](https://github.com/weDevsOfficial/wepos).

= Author =
Brought to you by [weDevs](http://wedevs.com)

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Frequently Asked Questions ==
No FAQ

== Screenshots ==
1. Overview
2. Product Search and Barcode Scan
3. Product list view
4. Customer Search
5. Add New Customer
6. Add discount and fees
7. Payment Page
8. Payment Receipt Page
9. Admin Dashboard Settings

== Changelog ==

= v1.0.3 -> 8 April, 2019 =
----------------------------
- **Fix**   Undefined issue in admin settings page
- **Tweak** Remove some unwnated code
- **Tweak** Modal component load globally and add more customizable options
- **Tweak** Update some flaticons

= v1.0.2 -> 25 Mar, 2019 =
----------------------------
- **New**   Added billing address missing fields in customer create
- **New**   Added all category selection in category filter
- **New**   Add extra product info in product list view
- **New**   Add Dokan plugin support
- **Tweak** Change quick menu layout to popover
- **Tweak** Change routing and menu rendring system for future extends
- **Fix**   Case sensitive issue in product search
- **Fix**   Remove attributes for simple product in cart and payment page
- **Fix**   Cursor poiting issue in keypads and other buttons
- **Fix**   Fee and discount calculation issue large amount(Price) of products
- **Fix**   Tax and fee tax calculation problem for percentage fees
- **Fix**   Product thumbnail resolution issue
- **Fix**   Rounding problem in cash and change amount after payment

= v1.0.1 -> 4 Mar, 2019 =
----------------------------
- **Fix**    Product fetching issue when no products found
- **Fix**    Customer data not reset during empty cart or new sales
- **Fix**    Event bus not triggering properly
- **Fix**    Render only publishable product in pos system
- **Tweak**  Added wp hooks for load action and filters

= v1.0.0 -> 22 Feb, 2019 =
Initial version released

== Upgrade Notice ==
No upgrade notice