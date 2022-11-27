---
title: Staff Check Gift Card
weight: 120
---

You may want to allow some people in your company (staff) to check for gift card information without giving them access to your Joomla!'s back-end.

To do this, you need to create Joomla! user accounts for your staff members, add these Joomla! users to the user group which you have selected for `Staff's User Group` option in CM Gift Card's configuration.

![](/images/configuration_03.jpg)

There are 2 menu item types that staff can use to manage gift cards: `Check Gift Cards` and `Staff Area`.

![](/images/menu_item_types.jpg)

## Check Gift Cards Menu Item Type

`Check Gift Cards` menu item type is where staff can see the list of all the gift cards on the site. If you access the new menu item for `Check Gift Cards` as a regular user (the one who is not in Staff group), you will receive an error:

![](/images/staff_01.jpg)

Staff can search for gift cards by gift card code, customer's name and address, gift card type, order status and delivery status.

![](/images/staff_02.jpg)

To view gift card detail, you need to create `Check Gift Card Detail (hidden menu item)` menu item type.

Click on gift card code to view gift card's detail.

![](/images/staff_03.jpg)

## Staff Area Menu Item Type

`Staff Area` menu item type was introduced since CM Gift Card 2.2.0, the page provides a QR code scanner to help staff to find gift card and set it redemption status faster.

When you access the QR code scanner, your web browser asks you permission to access your device's camera, you need to give your browser this permission.

A modal appears with the gift card's info after you scan the gift card code, you can set the redemption status by clicking the buttons `Redeem` and `Cancel Redemption`.

![](/images/qr_code_scanner_02.jpg)