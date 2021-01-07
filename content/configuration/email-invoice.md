---
title: Email & Invoice
weight: 60
---
![](/images/configuration_09.jpg)

* **Send A Copy Of Email To Administrators**: If you enable this option, administrators will receive a copy of customer's order email which is sent to customer after purchase is completed.
* **Prefix For Copied Email's Subject**: If you send a copy of customer's order email to administrators, you can use this option to add a special prefix to email subject. This gives you ability to filter these emails easily in your inbox.
* **Attach PDF Invoice To Order Email**: Attach PDF invoice for customer's order in the email sent to him/her.
* **Invoice Template**: You design your invoice template by using HTML and CSS. You can use the following tags in the template, these tags are replaced by actual information when invoice is generated:

  * `{customer_name}`: Customer's name
  * `{customer_email}`: Customer's email address
  * `{customer_address_1}`: Customer's address line 1
  * `{customer_address_2}`: Customer's address line 2
  * `{customer_address_3}`: Customer's address line 3
  * `{customer_postal_box}`: Customer's postal box
  * `{customer_city}`: Customer's city
  * `{customer_state}`: Customer's state
  * `{customer_postal_code}`: Customer's postal code
  * `{customer_country}`: Customer's country
  * `{order_number}`: Order's number
  * `{order_date}`: Order's completed date or created date
  * `{payment_method}`: Payment method's name
  * `{transaction_id}`: Transaction ID
  * `{order_items}`: List of order items

`{order_items}` is replaced by the HTML code of order item's list. This HTML code is generated from the file `/administrator/components/com_cmgiftcard/layouts/invoice_items.php`. To customize this HTML, you go to the folder `/administrator/components/com_cmgiftcard/layouts` and clone the file `invoice_items.php` to `invoice_items_custom.php`, you can modify the code of `invoice_items_custom.php` to suit your needs, the code of this file will be used to generate the HTML of order item's list.