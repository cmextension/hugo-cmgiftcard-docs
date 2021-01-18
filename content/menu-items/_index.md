---
title: Menu Items
weight: 30
---
![](/images/menu_item_types.jpg)

There are 8 menu item types available for CM Gift Card:

* **Default**: the page where your customers select the gift card types they want to buy.
* **Shopping Cart**: this is where customer provides billing and shipping details, then proceed to checkout.
* **Checkout**: this page is used to redirect customer to the selected payment gateway's website, it should be used as a hidden menu item.
* **Gift Card Form**: the page where customer selects gift card designs, enter gift card's amount...
* **Orders**: the list of customer's orders.
* **Order**: this is order detail page, it should be used as a hidden menu item.
* **Check Gift Cards**: this page is used by the site's staff, it shows all gift cards on the site.
* **Check Gift Card Detail**: this page is used by the site's staff for checking gift card detail, the page should be used as a hidden menu item.

Hidden menu items are the menu items which are not shown in your site's front-end. To create hidden menu item:

* You create a new menu, give this menu a title (whatever you like, for example `Hidden menu`).
* Create new menu items in this new menu.

As long as you don't assign this new menu to a menu module and show the module in your front-end, the menu items in this menu are also not shown in your front-end, they are considered "hidden".

The purposes of hidden menu item are giving us ability to control the URL of the page (via menu item's alias) and control what modules are shown on the page.