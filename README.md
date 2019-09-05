# Commerce Product Type Switcher

*NB this plugin assumes you have the same fields setup on each product type*

A lotof users on Craft Commerce have been asking for the ability to switch product types on the actual product itself. There is a simple way of doing it but it requires some db fiddling which can be dangerous if you have a client site that has high activity and admins changing product data on an hourly basis.

What this plugin aims to do is allow anyone to select a product type in the product admin cp edit page and use that to swap the product type manually.

**The idea**

1. Admin user goes into product and checks info but needs to change the product type for internal reasons or theres an issue with that product type itself.

2. They find the 'Change product type' dropdown and select the type they want to change to

3. Once saved the product type id column gets updated with the chosen type id that is selected from the dropdown.

4. Once it reloads the products index you will see that the product you were editing belongs to the new selected type you changed it to
