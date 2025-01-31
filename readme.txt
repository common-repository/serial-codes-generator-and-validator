=== Serial Codes Generator and Validator with WooCommerce Support ===
Contributors: Saso Nikolov
Tags: serial generator, code generator, serial validator, code validator, license keys, software license,
Requires PHP: 7.0
Stable tag: 2.7.3
Tested up to: 6.6
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

With support as WooCommerce serial generator for your sale and on your WooCommerce PDF Invoices
You can create and generate serials and codes. Print them on your products boxes or manuals. Your customer can check if the code is valid on your website. The Premium allows you also to activate user registration and more. This allows your user to register them self to a serial number.
Generate numbers and serial codes that can be validated on your site. It is a good plugin for small businesses that want an easy solution to create a large amount of numbers or serials and store them. It can for example be used to create numbers and serial codes for products and let users validate them on your site.

== Description ==
Manage your Serial Codes the easy wat.
https://youtu.be/DoNPvD3c6eM
[Video](https://youtu.be/DoNPvD3c6eM)

Allows you to manage codes (serial numbers) for your digital licensed products and physical products. Your user enters the code on your page and checks if the code is valid.

Optional for you is the included support for Woocommerce products and WooCommerce PDF Invoices - generate your WooCommerce serial directly with a purchase.

["Check out the overview video"](https://www.youtube.com/watch?v=DoNPvD3c6eM)

**If you use woocommerce, you can uset the option to auto generate a serial code for each sold product!**

**WooCommerce is NOT required, but just additional supported by our plugin if needed by you.**

**Shop:** With Serial Code Generator your will be able to sell license keys and products with a serial number or activation key. The plugin can create the code on the fly or use unused serials from your code list for each sold item.

**Validation of serials:** You customer can validate a serial on your page. The code generator gives you a flexible pattern to generate codes upfront. You can also **import your existing codes**.

**Build your own stolen serial database:** Support your customer and yourself to protect stolen products to be sold to others. Mark reported stolen products as stolen and let others check the serials.

**How can you setup the serial code generator?**
You can enter your codes within the WP admin area in the serial code section (a new menu point in the wordpress amdin area).
You can add your own codes manually using the serial code generator or import existing codes.
The codes can also be generated by the plugin. The serial code generator can create a bulk of serials or numbers as codes.
And you are also able to add your own codes by just entering them to the generated codes below the serial code generator.
If needed you can assign the codes to a list. The list (code list) helps you to organize the codes. The code list can be assigned to a WooCommerce product, if you want to add a serial code to each sold product.
Create one or more code lists to use the WooCommerce functionality.

**How the serial code generator works**
You define your look and feel for your codes. The generated codes will be unique. After you are satisfied with the generated codes, you can start the code adding step.
The code adding step will check if the code is unique on the server before adding it.
If the code (serial number/ticket number) exists already on the server, it will not be added.

= The generator provides a lot of features: =
- Code prefix - you can enter a fixed prefix to each code
- Length of code
- Only letters
- Uppercase, Lowercase or both
- Exclusion of letters that are easy to missread (i,l,o,q,p)
- Delimiter possible: [None, -, :, SPACE] - you decide after how many letters within the code
- CVV code generation (only numbers)

== Features ==
* Limit purchase of WooCommerce products to people with a specific code (restriction feature)
* Store WooCommerce orderid, itemid and productid to a serial code that was generated or used for a product sale
* You can now set the serial code format for all WooCommerce product that are using a serial code
* You can now set the serial code format directly on the WooCommerce product detail page if needed
* Use your serials to restrict purchases to allow a purchase of this product only if the buyer has a code for it (purchase allowance code)
* Add your own messages for the serial code validation form for your customers
* Add your own message for the "product stolen" validation message
* Disable the validation form for not logged in wordpress user
* User can register to a code (with wordpress user id if needed) after the code is checked - this makes your code one-time usable
* Display registered user information of a code during the validation if you need this
* One time check is possible (with wordpress user id if needed) - the code will be marked as used after the check
* One time check can have a maximum check amount based on code list or based on the global setting
* Several checks allowed - the code will be marked as used after X confirmed checks
* The user can be forwared (redirected) to an URL after the code was checked - to show more details
* Webhooks - you can inform other systems about code validation steps by entering for serveral serial code status during the validation check
* Display assigned serial codes to your user with a shortcode [sngmbhSerialcodesValidator_code]

== Premium Features ==
* Unlimited Codes (the basic allows you 500 serial codes)
* Unlimited Code Lists
* Save IP address of user using the code validation check on your page
* De- and re-activate codes
* Block IPs after x retries within 60 minutes - prevent brute force
* One time usage overuled by code list setting
* Enter expiration date for codes
* Enter expiration date for code lists (code overrule list expiration date)

Try it out first, before you go Premium. ["Here you can find the premium plugin"](https://vollstart.com/).

== Build your own Stolen products database ==
You can set the status of a serial code to be marked as stolen. This way you can offer your customers a way to report a stolen product. Other buyers of used products can validate the code on your website and will be notified with a "Product is stolen" warning.
This could increase sales and help reducing theft of your products.
The check behaviour will be like "inactive serial codes" but with the stolen message. You can change the stolen message within the options area of the serial code admin.

== Protection with CVV ==
You can set a code verification value (CVV) to protect your serial code. This allows you to print your serial code on the visible side of your product and print the CVV number on the open visible part of your packaging of your products. The validation check will ask the user to enter both for a valid check.
That way you increase the security of your serial codes and prevent stealing the serial code (If you are able hide the CVV on your packaging).
If you use a CVV on a serial code , then the user will be asked to enter this CVV too. If the CVV on your code is not set or empty it will be ignored and your customer is not asked for it.

== Woocommerce support for auto-generating serial codes ==
**Supports version 6+**
**You can use this plugin to auto-generate serial codes for your woocommerce products**
* Create a code list
* Go to your WooCommerce product and edit the product which should receive a serial code
* Click on "Serial Codes and Sale Restrictions" in the attribute area of your product
* Choose the "Code list" that will be used for this product

Everytime this product is sold, it will get a new generated serial code or use an unused serial code within your list (This need to be activated within the option settings). The new serial code will be added to the code list you set on your WooCommerce product and to the product sale too.
If the sold product quantity in the order is more than 1, then a code will be generated for each element. The code will be generated after the purchase. In case of a refund the serial code will be recovered and marked as unused, so that it can be reused.

*E.g.: Your customer bought 2 of the same product within one order, then 2 serials will be generated and stored to the product item within this order.*

= WooCommerce Serial Code Features =
* Automatically create and assign serial codes for physical products and digital products
* Recover serial code assigned to refunded orders
* Option to reuse the recovered serial codes with the latest orders
* Automatically deliver the serial codes with the complete order email
* Automatically deliver the serial codes with the optional PDF invoice "WooCommerce PDF Invoices"

== Woocommerce support product purchase restriction ==
**You can use this plugin to protect the sale of a product without a purchase code**
* Create a code list
* Add codes to this list - these codes will be the allowance-code to purchase a specific product
* Go to your WooCommerce product and edit the product which should be restricted for buy-only-with-serial-code
* Click on "Serial Codes and Sale Restrictions" in the attribute area of your product
* Choose the "Code List for sale restriction"
* Activate the option "Activate the purchase restrictions of product sales without a valid and unused serial code"

**Please note:**
If you exceed your limit (*no limits for premium user*) of the amount of possible codes, then the code added to the sold product will be a text information: **"Please contact our support for the serial code"**.
This way your business is not harmed and your customer can contact you to get a serial code manually. The format of the serial code will be **12345-12345-12345-12345** if you do not set a generation format within the options.

== WooCommerce PDF Invoices support to display the serial codes on the PDFs ==
If you use ["WooCommerce PDF Invoices"](https://en-gb.wordpress.org/plugins/woocommerce-pdf-invoices-packing-slips/), then the generated serial codes are displayed on the generated PDFs too!
The supported PDF plugin is from Ewout Fernhout.

== WooCommerce Product Sale Restriction to code only ==
You can restrict purchases for a product to a code from a code list or any code you have. The purchase will mark the code as used and cannot be reused for the next purchase.
This allows you to offer products that can be only bought by customers, that have received already the purchase code.

== Frontend ==
* Use the shortcode **[sngmbhSerialcodesValidator]**
* Create a page or use an existing one and add the shortcode to the page
* The shortcode will be replaced for your users by a form to enter the code and a button to validate the serial code. This allows you to surround the form with your own heading and instruction.
* Each code has a display version (e.g. XYZXYZ -> XYZ-XYZ), so it is easier for your user to read the serial code.
* The check will remove the display delimiter "-", ":", " " for the check automatically.
* So your user can enter the code with or without delimiters.

If you use CVV on a code and the user enter the code that requires a cvv, then your user will be ask to enter the CVV.
The user could enter the CVV immediately with the code. Separate the value with a ":". E.g: XYZXYZ:1234.

It is possible to prefill the serial code validation form with a code.
Add the parameter "code" to your page URL to create a link that prefills the form.
*E.g https://vollstart.com/serial-codes/?code=123-456-789*

= Form Options for expert =
You can use your own input, trigger and output HTML element.
Add the id parameter to your HTML elements and pass them to the shortcode as corresponding parameter.
You can add also your own JS function name that will be called before the code is checked on the server and also if the result comes back.
*[sngmbhSerialcodesValidator inputid="" triggerid="" outputid="" jspre="" jsafter=""]*
[Read here more about this feature](https://vollstart.com/serial-codes-validator-premium/docs/#styling)

== Quick overview ==
Each code is unique. The list is for your organisation and for your WooCommerce products.

= Plugin administration - where to find the plugin management area =
*It will add a new menu entry "Serial Codes Validator" within the settings section.*

[More about the plugin on our website](https://vollstart.com/serial-codes-validator-premium/first-steps)

== Support ==
Write to support@vollstart.com for support request.
For both plugins: The basic free and for the premium plugin.
We are here to help you.

== GETTING STARTED ==

A Quick start is shown in this [video](https://vollstart.com/serial-codes-validator-premium/first-steps).
A good first start is to open the serial code admin area and create a code list first.
Then add your codes by importing (add button at the code table) or assign the code list to your products.
Check out all the possible options in the serial code admin area to understand, how to tweak your usages of serial codes.
If you need a validation form for your users, to check the code, then please add the shortcode **[sngmbhSerialcodesValidator]** to a page.

= Steps to start =
- Go to the settings and click on menu "Serial Codes Validator".
- Click on button "Add" next to the heading "Codes".
- Enter you codes or generate codes using the built in serial code generator.
- Save your codes.
- Add the shortcode **[sngmbhSerialcodesValidator]** to a page.

== Premium Features ==

The **premium plugin** is now available with a lifetime license and 1 year support.

= Your benefits =
- Unlimited Code Lists
- Unlimited Codes
- Upload CSV file for massive codes import
- Assign serials to existing WooCommerce orders
- Save IP address of user using the code validation check on your page
- De- and re-activate codes
- Block IPs after x retries within 60 minutes - prevent brute force
- One time usage overuled by code list setting
- Enter expiration date for codes
- Enter expiration date for code lists (code overrule list expiration date)

**Checkout the premium plugin and planned features: [Serial Code Generator and Validator Premium](https://vollstart.com/serial-codes-validator-premium/)**

== Installation ==

* WordPress 5.0 or greater
* PHP version 7.0 or greater
* MySQL version 5.0 or greater

= Installation =

1. Install the pluging using the WordPress built-in Plugin installer.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to "Settings" > "Serial Codes Validator" and add codes.
4. Add the shortcode **[sngmbhSerialcodesValidator]** to a page to display the code validation form.

**For more help and your first steps, please [visit our website](https://vollstart.com/serial-codes-validator-premium/first-steps/)**

== Screenshots ==

1. **Management Area** You can manage lists and see all codes. The code list is searchable.
2. **Codes Generator** Set the settings and generate codes. Or enter your own.
3. **Frontend** The shortcode will be replaced by a form. The checks deliver different messages.
4. **Options 1** Validation messages
5. **Options 2** User & Login tracking
6. **Options 3** Registration to code & Display information to the user
7. **Options 4** User redirection & Webhooks
8. **WooCommerce product 1** Set up your products to use the serial codes

== Upgrade Notice ==
= 2.4.12 =
Ticket option will be removed. We have too many issues with it and the sister plugin "Event ticket with ticket scanner" is doing a much better job.

= 2.4.4 =
BACKUP your database!! Tables are going to be migrated if you are not a premium user to match them and allow you to upgrade without loosing your codes.

= 2.4.3 =
Emergency update. The version 2.4.3 had a mistake, that can prevent purchases being processed. Please update to this or newer version. I am deeply sorry for this.

= 2.2.1 =
Changes are made, how the classes and objects are working together. It is important to update the premium version also, as soon as it is available.

= 2.2.0 =
New Ticket Sale via WooCommerce included. Check out the new feature.

= 2.1.14 =
Add new seperator option for serials printed on PDF invoices and on the "complete order" email. Check out the new option values.

= 2.1.12 =
New URL replacement tag {LIST_DESC} added for your redirect and webhook URLs

= 2.1.7 =
You can now set the serial code format directly on the WooCommerce product detail page if needed. New sales of the product will use the format settings if activated.

== Changelog ==
= 2.7.3 - 2024-08-30 =
* Fix the cart issue for serial code restriction products with different product type in the cart

= 2.7.2 - 2024-07-09 =
* Bug fix for the removal of serial if the order was refunded. If option wcRestrictFreeCodeByOrderRefund is active and the order will be set to refund, then the serial will be removed.
* Added support for QR code images

= 2.7.1 - 2024-06-17 =
* Add support for old premium version with ticket sales
* Added search filters to choose from
* Enhanced the search for codes. You can add now a text search value if you filter for a code list

= 2.7.0 - 2024-06-11 =
* Removed the deprecated ticket options and input fields
* Adjustments to use vollstart.com

= 2.6.3 - 2024-04-16 =
* Fix CVV value for the code parameter on the validator form

= 2.6.2 - 2024-04-02 =
* Add support for serials with non ansi code serials like Umlaute
* Check for the expiration of the support for premium license added
* Fix cronjob removal from the wordpress installation with the deactivation of the plugin

= 2.6.1 - 2024-03-12 =
* Bug fix for the registration of the order user id to the serial automatically with the purchase - autoUserRegisterToCodeWithOrder
* Preparation to support premium update notifications

= 2.6.0 - 2024-03-06 =
* Bug fix to ask for restriction code if all codes are allowed
* New feature: You can now extend the expiration date of a code that is used as a restriction code. This allows you to sell update (products), that are extending the used serial code for the purchase of the restricted product. The days can be entered within the product details. PREMIUM only.

= 2.5.11 - 2024-02-16 =
* Bug fix expiration date evaluation
* Change the deeplink to the order from the admin area to edit the order directly

= 2.5.10 - 2024-01-22 =
* Bug fix for loop call on the QR code URL

= 2.5.9 - 2024-01-18 =
* New feature on the product to print all QR codes of the serials

= 2.5.8 - 2023-12-26 =
* The additional informations are now also displayed if the code is not only valid, so always if the code was able to be found

= 2.5.7 - 2023-12-21 =
* Used status is now on its own column and can be sorted

= 2.5.6 - 2023-12-12 =
* New option to register the user of the order automatically to the purchased code(s) - autoUserRegisterToCodeWithOrder

= 2.5.5 - 2023-11-20 =
* Add product option to have more than one serial per purchased item

= 2.5.4 - 2023-10-06 =
* Add new option to display and export the customer billing name
* Import code list also with redirect option and url

= 2.5.3 - 2023-09-05 =
* fix for the JS tag remover

= 2.5.2 - 2023-08-30 =
* Improved speed for the serial validator form loading
* Added the option names to the option labels for better and easier reference
* Removed the ob_flush (used for the tickets) to speed up the solution

= 2.5.1 - 2023-08-23 =
* Improved escaping for list name
* Stolen serial with CVV is fixed and display correct the stolen message
* Added import of Code Lists

= 2.4.15 - 2023-08-16 =
* Support for Serial Code Validator API
* Small bug fixed
* Tickets removed
* XSS issue with code and list name fixed

= 2.4.14 - 2023-06-11 =
* New webhook for usage of restricted code on order item
* Fix for UTF8 codes

= 2.4.13 - 2023-03-09 =
* Access to admin area can be controlled by roles

= 2.4.12 - 2023-02-28 =
* Deprecate ticket option - will be removed soon

= 2.4.11 - 2023-02-15 =
* Fix WC_VERSION check
