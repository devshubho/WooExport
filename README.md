=== ExportMate ===
Contributors: devshubho
Tags: woocommerce, export, csv, customer, email, admin, report
Requires at least: 5.5
Tested up to: 6.8
Requires PHP: 7.2
Stable tag: 1.1
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Export WooCommerce customer data for specific products into CSVs. Download, email to admin, or send to any email. Built with ❤️ by Dev.Shubho.

== Description ==

**ExportMate** lets you export product-specific WooCommerce customer data into CSV files. Select fields, enter product ID, and choose whether to download the CSV, email it to the site admin, or a custom email.

== Features ==

* Export customers by WooCommerce Product ID
* Select data fields: name, email, phone, product name, date
* Choose export destination:
  * 📥 Download CSV
  * 📧 Email to admin
  * ✉️ Email to custom address
* Sends email with CSV as attachment
* Clean UI in WordPress admin
* Plugin built by Dev.Shubho

== Installation ==

1. Upload the plugin folder to `/wp-content/plugins/` or install via WordPress admin dashboard.
2. Activate the plugin through the 'Plugins' menu.
3. Go to **WP-ExportMate** in the WordPress admin sidebar.
4. Select fields, enter product ID, choose how to export (download/email), and hit Export.

== Screenshots ==

1. Admin export panel
2. Field selection and product ID input
3. Destination options: download or email

== Changelog ==

= 1.1 =
* NEW: Choose to download CSV, email to admin, or email to custom address
* CSV file is attached in email
* Field added for entering custom email address

= 1.0 =
* Initial release: download CSV of customers by product ID with field selection

== Frequently Asked Questions ==

= Does it support custom order statuses? =
Currently only exports `completed` orders.

= Where can I find the product ID? =
In your WooCommerce Products list, hover over the product title. The ID will be shown below the product name.

= Can I export to Excel? =
Yes! The downloaded CSV is Excel-compatible.

== License ==

This plugin is licensed under the GPLv2 or later. You may modify and redistribute it freely.
