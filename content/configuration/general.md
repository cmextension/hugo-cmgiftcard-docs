---
title: General
weight: 10
---
![](/images/configuration_03.jpg)

* **Gift Card Types**: Select the gift card types which you want to sell on your site.
* **Gift Card Design Popup**: If you enable this option, customer can view gift card design in a popup after clicking the gift card design's thumbnail.
* **Staff's User Group**: Select a Joomla! user group which your staff is in. Only the Joomla! users in the selected group have ability to check gift card's info in front-end.
* **Terms of Service**: Show or hide Terms of Service checkbox when checkout.
* **Terms of Service Menu Item**: The menu item of Terms of Service page, this page is opened when we click on the Terms of Service link in checkout page.
* **Max Delivered Gift Cards In Every Cron Job Run**: The maximum quantity of electronic gift card email is sent every time cron job runs. Too many emails sent could lead to an timeout error.
* **Cron Job's Secret Key**: The key is used in cron job's URL, eg. `yourdomain.com/index.php?option=com_cmgiftcard&task=cron.deliverElectronicCards&key=YOUR_KEY_HERE`. If the key is not provided, cron job doesn't run. 