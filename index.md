# Pdf Vouchers for TastyIgniter

Create Customizable PDF Vouchers for In-Store or Online Redemption

PDF Vouchers helps you connect your online store to an physical business, providing printable gift certificates to be used in person, online, at events, in exchange for free gifts, and more!

With  coupons you can offer discounts to your customers but you cant sell these coupons as store credit and they cant be redeemed in-person at your fisical locations.

PDF  Vouchers is perfect for businesses that accept orders online but provide a good or service at a later date or in-person.
Vouchers can be used for pre-paid admission to your cooking class, tickets to an event, as gift certificates or to provide as redemption for a free gift when visiting a retail location.

Product vouchers also make an attractive gift for customers to purchase for their friends and family.

### How can PDF Vouchers help you and your business

- Customize and sell downloadable PDF vouchers
- Sell vouchers that can later be redeemed in your online store
- Include QR codes on vouchers so you can quickly redeem them with a single scan
- Creating voucher templates uses a "what you see is what you get" editor
- Includes 3 default voucher backgrounds, or you can upload your own
- View a list of all generated vouchers or search by voucher number to find a customer's voucher
- Manage vouchers from the voucher list and mark them as redeemed when needed
- Mark a voucher as disabled to block further redemptions
- Manually create vouchers for customers to give away store credit

### Create a voucher menu item

You can create a voucher product by enabling switch then compile necessary fields, when a customer buy a voucher menu item a new voucher will be generated with its values and sent as attachment by mail to the customer (if the option is enabled on the vouchers settings and the payment method is authorized).

The locations fields can be used to limit a use of the voucher to a selected location(s)

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_menu_item.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_menu_item.png)


### Easily Build Voucher Templates

You can build a voucher template, which is attached to products to generate a PDF with your customer’s details. These templates let you place fields of the voucher, edit fonts or color, and more:


[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_2.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_2.png)

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_1.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_3.png)

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_3.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_template_editor_3.png)


Customers will receive a email with voucher as attachment once the order has been paid for, if a order has a payment method that is set in "Excluded payment method" in the Voucher settings page the voucher will be created disabled and don't will be sent to email customer, can be sent after by operator from the backend area.

**PDF voucher come with four ready to use template and gift cards demo example that will be created on install.**

### Use voucher on your site

To display the voucher form on your site cartbox, you will need to add the voucherForm component to both the default and local layouts, and manually insert **@component('voucherForm')** into the cartbox/default.blade.php file of the cart extension. It is recommended to place it after the coupon components.

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_form_cartbox.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_form_cartbox.png)

### Show vouchers on account area

Registered customers on your store will be able to download vouchers they've purchased from the account area in addition to getting emails with voucher attachments , you will need to add the **@component('accountVouchers')** to a new account vouchers page and add a link to the page in to account/sidebar partials

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/account_vouchers.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/account_vouchers.png)

### Scan QR codes for redemption

If you need to quickly redeem vouchers in-person include a QR code on your vouchers!
You can then scan the codes with a mobile or any device with a camera to redeem them in seconds:

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/scan_voucher.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/scan_voucher.png)

### Administration tool

When a voucher menu item is purchased, a new voucher will be generated for the customer under your "Vouchers" list.

You can filter this list as usual and change status of the vouchers or send them via bulk actions

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_list.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/voucher_list.png)

In edit page you can see voucher details, send a mail with voucher as attachment, change template e regenerate pdf.
You can also view the order from which the voucher was generated and the details of the redemption such as date and time and if has been redeemed by a customer or staff.

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/edit_voucher.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/edit_voucher.png)



### Voucher settings

In voucher settings ou can set a voucher durations, the excluded payment methods, enable/disable sending voucher by mail on purchase, format of the expiring date on the created vouchers, use of the currency simbol for the value and the characters limit of  description if present on the voucher

[![](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/vouchers_settings.png)](https://raw.githubusercontent.com/Concreta09/tasty-pdf-voucher-doc/gh-pages/ouchers_settings.png)
