# Tastyigniter-extensions-igniter-cart-language-en-default.php
Various message Changes and added missing igniter.cart::default.alert_min_order_total' in default.php


This message appeared on the website because it is a predefined error message in the Igniter Cart plugin. The message is triggered when a user tries to checkout with a cart total that is below the minimum order amount set for the location.
However the message was "igniter.cart::default.alert_min_order_total" we know what this means, but not the end user so I added it to the default.php file. 
Now all is good and shows the user a simple message:
"There is a minimum order amount that must be met for delivery. Please add more items to your cart to meet the minimum order total of $10.00." or whatever your min is.

This should make it clearer and easier for customers. I know you guys work hard and keep up the good work!
