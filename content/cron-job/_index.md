---
title: Cron Job
weight: 140
---
To send electric gift card to recipient on the delivery date which sender has chosen, you need to setup for a cron job to run at least once a day to check and send the gift cards of the current date.

Each hosting has its own way to setup cron job. If you are not sure how to setup cron job for your hosting, please contact your hosting provider for more information.

The general command to run CM Gift Card cron job is:

`wget https://yourdomain.com/index.php?option=com_cmgiftcard&task=cron.deliverElectronicCards&key=YOUR_SECRET_KEY_HERE > /dev/null 2>&1`

or 

`curl https://yourdomain.com/index.php?option=com_cmgiftcard&task=cron.deliverElectronicCards&key=YOUR_SECRET_KEY_HERE > /dev/null 2>&1`

Replace `https://yourdomain.com` with your site's URL and replace `YOUR_SECRET_KEY_HERE` with the secret key which you configure in CM Gift Card's configuration.

If you want to test if the URL above sends gift cards or not, you can access it directly on your browser, you will receive messages in this format if there are gift cards sent:

`Sent email for card #12345`

If there is no gift cards to send, you will get this message:

`No electronic gift cards found`