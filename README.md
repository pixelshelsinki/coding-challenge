# PIXELS Code Challenge v2.0
Challenge for job applicants

## TASK
Please use this boilerplate to implement the app outlined in `MiniShop.pdf`
Feel free to remove anything you deem unnecessary from this boilerplate :)

# FEATURES
The app simulates a very small shop.
The columns need to be implemented with [flexbox](http://caniuse.com/#search=flexbox).
You should start by loading the instructions from `/data/instructions.json` into the first column.
Then when the "Fetch Products" button is clicked you should fetch the products from `/data/products.json` and display the products as shown in the pdf.
There should be pagination
Add a 'type to search' box to filter by product name and description.

When there is at least one product in the "Cart" it should become possible to click the "Place Order" button. This triggers an alert with the contents of the cart.

## Notes:
- Each product can only be added to the cart once
- The SVG spinner should be visibly spinning when fetching the products
- Make sure to disable/ enable buttons when needed
- Notice the change of the column order on small screens!
- Please use Bootstrap 4, and show your ability to use Bootstrap 4's built in components, rather than creating your own from scratch.

# BONUS
- Nice transitions/animations :)
- Design improvements
- Use some nicer modal instead of pure js alert


This challenge should not take more than 4-6 hours of your time.
Wherever possible please use CSS animations/transitions.

Good luck!
