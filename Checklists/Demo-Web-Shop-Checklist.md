# Demo Web Shop — Test Checklist

## 1. Registration
- [ ] Verify that the Registration page displays all required fields: First name, Last name, Email, Password and Confirm password.
- [ ] Verify that the Gender field is optional.
- [ ] Verify that the Register button is displayed below the registration form.
- [ ] Verify that the Password field masks the entered characters.
- [ ] Verify that the Confirm password field masks the entered characters.
- [ ] Verify that the password requirement is displayed: at least 6 characters.
- [ ] Verify that registration accepts a password containing exactly 6 characters.
- [ ] Verify that registration is completed successfully when all required fields contain valid data.
- [ ] Verify that registration is blocked when Password and Confirm password do not match.
- [ ] Verify that the error message "The password and confirmation password do not match." is displayed when passwords differ.
- [ ] Verify that registration is blocked when an invalid email address is entered.
- [ ] Verify that the error message "Wrong email" is displayed for an invalid email address.
- [ ] Verify that registration is blocked when an already registered email address is entered.
- [ ] Verify that the error message "The specified email already exists" is displayed for an already registered email address.
- [ ] Verify that registration is blocked when all required fields are empty.
- [ ] Verify that the required-field validation messages are displayed for First name, Last name, Email, Password and Confirm password.
## 2. Login / Logout
- [ ] Verify that the Login page displays the Email and Password fields.
- [ ] Verify that the Log in button is displayed below the login fields.
- [ ] Verify that the Remember me checkbox can be selected and deselected.
- [ ] Verify that the Forgot password link redirects to the Password recovery page.
- [ ] Verify that the Password recovery page displays the required Your email address field.
- [ ] Verify that the Recover button is displayed on the Password recovery page.
- [ ] Verify that a user can successfully log in with valid credentials.
- [ ] Verify that login is blocked when an invalid password is entered.
- [ ] Verify that the appropriate error messages are displayed when invalid credentials are entered.
- [ ] Verify that login is blocked when the Email and Password fields are empty.
- [ ] Verify that login is blocked when the Password field is empty and a registered email address is entered.
- [ ] Verify that login is blocked when the Email field is empty and a password is entered.
- [ ] Verify that the appropriate error messages are displayed for empty login fields.
- [ ] Verify that a user can successfully log out.
- [ ] Verify that the Log in link is displayed after logout.
## 3. Search
- [ ] Verify that the search field is displayed on the website.
- [ ] Verify that search returns a matching product when a valid product name is entered.
- [ ] Verify that the product name and price are displayed in the search results.
- [ ] Verify that an appropriate message is displayed when no products match the search keyword.
- [ ] Verify that the message "No products were found that matched your criteria." is displayed when searching for a non-existent product.
- [ ] Verify that the Advanced search section can be expanded.
- [ ] Verify that the Category dropdown is displayed in Advanced search.
- [ ] Verify that the Category dropdown contains available categories and subcategories.
- [ ] Verify that the Automatically search sub categories checkbox is displayed and can be selected.
- [ ] Verify that the Manufacturer dropdown is displayed in Advanced search.
- [ ] Verify that the Manufacturer dropdown contains the All and Tricentis options.
- [ ] Verify that the Manufacturer filter can be selected.
- [ ] Verify that searching for "Laptop" with Manufacturer set to "Tricentis" displays the no-results message.
- [ ] Verify that the Price range fields (From and To) are displayed.
- [ ] Verify that products within the specified price range are displayed in search results.
- [ ] Verify that the 14.1-inch Laptop priced at 1590.00 is displayed when the price range is set from 1000 to 2000.
- [ ] Verify that products priced below the specified minimum price are excluded from search results.
- [ ] Verify that products priced above the specified maximum price are excluded from search results.
- [ ] Verify that the Search In product descriptions checkbox can be selected.
- [ ] Verify that enabling Search In product descriptions returns additional products matching the keyword in their descriptions.
- [ ] Verify that disabling Search In product descriptions excludes products that match the keyword only in their descriptions.
- [ ] Verify that search does not proceed when the search keyword contains fewer than 3 characters.
- [ ] Verify that the message "Search term minimum length is 3 characters" is displayed for a search term shorter than 3 characters.
## 4. Product
**Product Details**
- [ ] Verify that the Product Details page displays the correct product name.
- [ ] Verify that the product price is displayed.
- [ ] Verify that product availability is displayed.
- [ ] Verify that the product description is displayed.
- [ ] Verify that the product image is displayed.
- [ ] Verify that the number of customer reviews is displayed.
- [ ] Verify that the Add your review link is displayed.
- [ ] Verify that the Qty field is displayed.
- [ ] Verify that the product specifications section is displayed.
- [ ] Verify that product specifications are displayed correctly.
- [ ] Verify that product tags are displayed.
- [ ] Verify that related products are displayed in the Customers who bought this item also bought section.

**Product Quantity and Add to Cart**
- [ ] Verify that the Qty field allows the user to enter a product quantity.
- [ ] Verify that clicking Add to cart adds the selected product quantity to the Shopping Cart.
- [ ] Verify that the Shopping Cart displays the selected product quantity correctly.
- [ ] Verify that updating the product quantity in the Shopping Cart recalculates the total price correctly.
- [ ] Verify that a product can be removed from the Shopping Cart.
- [ ] Verify that the Shopping Cart displays an empty-cart message after all products are removed.
- [ ] Verify that adding a product with quantity 0 displays the validation message: `Quantity should be positive`.
- [ ] Verify that adding a product with a negative quantity displays the validation message: `Quantity should be positive`.
- [ ] Verify that entering a fractional quantity (1.5) displays the validation message: `Quantity should be positive`.
- [ ] Verify that adding a product with a valid quantity (1) succeeds.

**Product Reviews**
- [ ] Verify that clicking Add your review opens the product review page.
- [ ] Verify that the product review form contains the Review title field.
- [ ] Verify that the product review form contains the Review text field.
- [ ] Verify that the product review form contains the Submit review button.
- [ ] Verify that submitting the review form with empty fields displays the required-field validation messages.
- [ ] Verify that submitting the review form with a Review title but an empty Review text displays `Review text is required.`
- [ ] Verify that submitting the review form with an empty Review title and a filled Review text displays `Review title is required.`
- [ ] Verify that submitting a review with valid data displays the success message: `Product review is successfully added.`
- [ ] Verify that a successfully submitted product review is displayed on the product page.
- [ ] Verify that the displayed review contains the review title, review text, author, and submission date.
- [ ] Verify that the review displays the Was this review helpful? Yes/No options.
- [ ] Verify that clicking Yes in the review helpfulness section updates the helpfulness counter.
- [ ] Verify that clicking the Reviews link opens the product reviews page.

**Related Products**
- [ ] Verify that clicking a related product opens its Product Details page.
## 5. Shopping Cart
## 6. Checkout
