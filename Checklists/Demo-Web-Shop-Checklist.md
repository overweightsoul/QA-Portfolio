# Demo Web Shop — Test Checklist

## 1. Registration
- [x] Verify that the Registration page displays all required fields: First name, Last name, Email, Password and Confirm password.
- [x] Verify that the Gender field is optional.
- [x] Verify that the Register button is displayed below the registration form.
- [x] Verify that the Password field masks the entered characters.
- [x] Verify that the Confirm password field masks the entered characters.
- [x] Verify that the password requirement is displayed: at least 6 characters.
- [x] Verify that registration accepts a password containing exactly 6 characters.
- [x] Verify that registration is completed successfully when all required fields contain valid data.
- [x] Verify that registration is blocked when Password and Confirm password do not match.
- [x] Verify that the error message "The password and confirmation password do not match." is displayed when passwords differ.
- [x] Verify that registration is blocked when an invalid email address is entered.
- [x] Verify that the error message "Wrong email" is displayed for an invalid email address.
- [x] Verify that registration is blocked when an already registered email address is entered.
- [x] Verify that the error message "The specified email already exists" is displayed for an already registered email address.
- [x] Verify that registration is blocked when all required fields are empty.
- [x] Verify that the required-field validation messages are displayed for First name, Last name, Email, Password and Confirm password.
## 2. Login / Logout
- [x] Verify that the Login page displays the Email and Password fields.
- [x] Verify that the Log in button is displayed below the login fields.
- [x] Verify that the Remember me checkbox can be selected and deselected.
- [x] Verify that the Forgot password link redirects to the Password recovery page.
- [x] Verify that the Password recovery page displays the required Your email address field.
- [x] Verify that the Recover button is displayed on the Password recovery page.
- [x] Verify that a user can successfully log in with valid credentials.
- [x] Verify that login is blocked when an invalid password is entered.
- [x] Verify that the appropriate error messages are displayed when invalid credentials are entered.
- [x] Verify that login is blocked when the Email and Password fields are empty.
- [x] Verify that login is blocked when the Password field is empty and a registered email address is entered.
- [x] Verify that login is blocked when the Email field is empty and a password is entered.
- [x] Verify that the appropriate error messages are displayed for empty login fields.
- [x] Verify that a user can successfully log out.
- [x] Verify that the Log in link is displayed after logout.
## 3. Search
- [x] Verify that the search field is displayed on the website.
- [x] Verify that search returns a matching product when a valid product name is entered.
- [x] Verify that the product name and price are displayed in the search results.
- [x] Verify that an appropriate message is displayed when no products match the search keyword.
- [x] Verify that the message "No products were found that matched your criteria." is displayed when searching for a non-existent product.
- [x] Verify that the Advanced search section can be expanded.
- [x] Verify that the Category dropdown is displayed in Advanced search.
- [x] Verify that the Category dropdown contains available categories and subcategories.
- [x] Verify that the Automatically search sub categories checkbox is displayed and can be selected.
- [x] Verify that the Manufacturer dropdown is displayed in Advanced search.
- [x] Verify that the Manufacturer dropdown contains the All and Tricentis options.
- [x] Verify that the Manufacturer filter can be selected.
- [x] Verify that searching for "Laptop" with Manufacturer set to "Tricentis" displays the no-results message.
- [x] Verify that the Price range fields (From and To) are displayed.
- [x] Verify that products within the specified price range are displayed in search results.
- [x] Verify that the 14.1-inch Laptop priced at 1590.00 is displayed when the price range is set from 1000 to 2000.
- [x] Verify that products priced below the specified minimum price are excluded from search results.
- [x] Verify that products priced above the specified maximum price are excluded from search results.
- [x] Verify that the Search In product descriptions checkbox can be selected.
- [x] Verify that enabling Search In product descriptions returns additional products matching the keyword in their descriptions.
- [x] Verify that disabling Search In product descriptions excludes products that match the keyword only in their descriptions.
- [x] Verify that search does not proceed when the search keyword contains fewer than 3 characters.
- [x] Verify that the message "Search term minimum length is 3 characters" is displayed for a search term shorter than 3 characters.
## 4. Product
**Product Details**
- [x] Verify that the Product Details page displays the correct product name.
- [x] Verify that the product price is displayed.
- [x] Verify that product availability is displayed.
- [x] Verify that the product description is displayed.
- [x] Verify that the product image is displayed.
- [x] Verify that the number of customer reviews is displayed.
- [x] Verify that the Add your review link is displayed.
- [x] Verify that the Qty field is displayed.
- [x] Verify that the product specifications section is displayed.
- [x] Verify that product specifications are displayed correctly.
- [x] Verify that product tags are displayed.
- [x] Verify that related products are displayed in the Customers who bought this item also bought section.
**Product Quantity and Add to Cart**
- [x] Verify that the Qty field allows the user to enter a product quantity.
- [x] Verify that clicking Add to cart adds the selected product quantity to the Shopping Cart.
- [x] Verify that the Shopping Cart displays the selected product quantity correctly.
- [x] Verify that updating the product quantity in the Shopping Cart recalculates the total price correctly.
- [x] Verify that a product can be removed from the Shopping Cart.
- [x] Verify that the Shopping Cart displays an empty-cart message after all products are removed.
- [x] Verify that adding a product with quantity 0 displays the validation message: `Quantity should be positive`.
- [x] Verify that adding a product with a negative quantity displays the validation message: `Quantity should be positive`.
- [x] Verify that entering a fractional quantity (1.5) displays the validation message: `Quantity should be positive`.
- [x] Verify that adding a product with a valid quantity (1) succeeds.
**Product Reviews**
- [x] Verify that clicking Add your review opens the product review page.
- [x] Verify that the product review form contains the Review title field.
- [x] Verify that the product review form contains the Review text field.
- [x] Verify that the product review form contains the Submit review button.
- [x] Verify that submitting the review form with empty fields displays the required-field validation messages.
- [x] Verify that submitting the review form with a Review title but an empty Review text displays `Review text is required.`
- [x] Verify that submitting the review form with an empty Review title and a filled Review text displays `Review title is required.`
- [x] Verify that submitting a review with valid data displays the success message: `Product review is successfully added.`
- [x] Verify that a successfully submitted product review is displayed on the product page.
- [x] Verify that the displayed review contains the review title, review text, author, and submission date.
- [x] Verify that the review displays the Was this review helpful? Yes/No options.
- [x] Verify that clicking Yes in the review helpfulness section updates the helpfulness counter.
- [x] Verify that clicking the Reviews link opens the product reviews page.
**Related Products**
- [x] Verify that clicking a related product opens its Product Details page.
## 5. Shopping Cart
### Cart Contents
- [x] Verify that the Shopping Cart displays the cart items in a table.
- [x] Verify that the cart table contains the Remove, Product(s), Price, Qty., and Total columns.
- [x] Verify that the product image and name are displayed in the Shopping Cart.
- [x] Verify that the product price is displayed correctly.
- [x] Verify that the product quantity is displayed.
- [x] Verify that the product total is calculated correctly.
- [x] Verify that the Sub-Total, Shipping, Tax, and Total amounts are displayed.
- [x] Verify that the Terms of Service checkbox is displayed.
- [x] Verify that the Checkout button is displayed.
### Quantity and Remove
- [x] Verify that changing the product quantity and clicking Update shopping cart updates the product total.
- [x] Verify that the Shopping Cart recalculates the Sub-Total and Total after the quantity is updated.
- [x] Verify that selecting Remove and clicking Update shopping cart removes the product from the cart.
- [x] Verify that the empty Shopping Cart displays the message: `Your Shopping Cart is empty!`
### Discount Code
- [x] Verify that the Discount Code section is displayed.
- [x] Verify that applying an invalid discount coupon displays the message: `The coupon code you entered couldn't be applied to your order`.
### Gift Cards
- [x] Verify that the Gift Cards section is displayed.
- [x] Verify that the Gift Cards section contains the Add gift card button.
- [x] Check whether clicking Add gift card with an empty field displays the coupon error message: `The coupon code you entered couldn't be applied to your order`.
- [x] Check whether entering an invalid gift card code displays the same coupon error message.
### Estimate Shipping
- [x] Verify that the Estimate shipping section is displayed.
- [x] Verify that the country selection field is displayed.
- [x] Verify that the State / province field is displayed.
- [x] Verify that the Zip / postal code field is displayed.
- [x] Verify that selecting Germany displays the available shipping methods.
- [x] Verify that the following shipping methods are displayed: Ground, Next Day Air, 2nd Day Air, and In-Store Pickup.
- [x] Verify that the shipping cost is displayed for each available shipping method.
## 6. Checkout
### Payment Method
- [x] Verify that the Payment Method page displays the available payment methods.
- [x] Verify that Cash On Delivery (COD) is displayed with a fee of 7.00.
- [x] Verify that Check / Money Order is displayed with a fee of 5.00.
- [x] Verify that Credit Card is displayed as a payment method.
- [x] Verify that Purchase Order is displayed as a payment method.
- [x] Verify that the Back link returns the user to the previous checkout step.
### Payment Information
- [x] Verify that the Payment Information page is displayed after selecting Credit Card.
- [x] Verify that the Select credit card field displays Visa, MasterCard, Discover, and Amex.
- [x] Verify that the Cardholder name field is displayed.
- [x] Verify that the Card number field is displayed.
- [x] Verify that the Expiration date fields are displayed.
- [x] Verify that the Card code field is displayed.
- [x] Verify that the Back link is displayed.
- [x] Verify that the Continue button is displayed.
- [x] Verify that submitting the empty Payment Information form displays the validation message: `Enter cardholder name`.
- [x] Verify that submitting the empty Payment Information form displays the validation message: `Wrong card number`.
- [x] Verify that submitting the empty Payment Information form displays the validation message: `Wrong card code`.
- [x] Verify that entering a Cardholder name removes the `Enter cardholder name` validation message.
- [x] Verify that entering a valid test card number removes the `Wrong card number` validation message.
### Confirm Order
- [x] Verify that the Confirm Order page displays the Billing Address.
- [x] Verify that the Confirm Order page displays the Payment Method.
- [x] Verify that the Confirm Order page displays the Shipping Address.
- [x] Verify that the Confirm Order page displays the Shipping Method.
- [x] Verify that the order summary displays the product name, price, quantity, and total.
- [x] Verify that the Sub-Total is displayed correctly.
- [x] Verify that the Shipping cost is displayed correctly.
- [x] Verify that the Tax amount is displayed correctly.
- [x] Verify that the final Total is calculated correctly.
- [x] Verify that the Back link is displayed.
- [x] Verify that the Confirm button is displayed.
### Order Confirmation
- [x] Verify that clicking Confirm successfully processes the order.
- [x] Verify that the order confirmation page displays the message: `Your order has been successfully processed!`
- [x] Verify that a unique order number is displayed after successful checkout.
- [x] Verify that the Click here for order details link is displayed.
### Order Details
- [x] Verify that the Order Details page displays the correct order number.
- [x] Verify that the order date is displayed.
- [x] Verify that the order status is displayed.
- [x] Verify that the order total is displayed.
- [x] Verify that the Billing Address is displayed.
- [x] Verify that the Payment Method is displayed.
- [x] Verify that the Shipping Address is displayed.
- [x] Verify that the Shipping Method is displayed.
- [x] Verify that the ordered product name is displayed.
- [x] Verify that the product price and quantity are displayed correctly.
- [x] Verify that the Sub-Total, Shipping, Tax, and Order Total are displayed correctly.
### Order History
- [x] Verify that a successfully placed order is displayed in My Account → Orders.
- [x] Verify that the order number, order status, order date, and order total are displayed correctly.
- [x] Verify that clicking an order number opens the corresponding order details page.
