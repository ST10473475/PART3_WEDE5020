# PART3_WEDE5020
WEDE Submission Part 3

 
WEDE SUMMATIVE
WEDE5020
 
 
PART THREE CHANGES
1. Product Page Enhancements
•	Added data attributes for product price and name (data-price and data-name) for each product to support dynamic cart functionality.
•	Replaced all “Order” buttons with “Add to Cart” buttons and linked them to the shopping cart logic.
•	Structured product sections for Nike, Adidas, Puma, Louis Vuitton, and Christian Dior, making them consistent in layout and data.
•	Fixed image display sizes and added border-radius for cleaner visual styling.

2. Search Functionality
•	Implemented a search bar that allows users to filter products by brand or product name.
•	Search functionality uses JavaScript to dynamically show/hide products based on user input.

3. Shopping Cart Implementation
•	Created a shopping cart section visible on the product page.
•	Implemented local storage to save cart items so that the cart persists across page reloads.
•	Cart displays the product name, price, and a remove button.
•	Added a total price calculation that updates as items are added or removed.

4. Login Requirement for Orders
•	Integrated a modal popup for login/sign-up.
•	Modified the “Add to Cart” functionality so users must be logged in to add items to the cart.
•	Checkout also requires the user to be logged in before proceeding.

5. Checkout Functionality
•	Added a checkout button that:
o	Checks if the cart is empty.
o	Checks if the user is logged in.
o	Alerts the user with the total price.
o	Clears the cart after successful checkout.

6. CSS Styling Updates
•	Standardized header, navigation, and footer styling for consistent appearance.
•	Updated product card styling: borders, padding, background, hover effects.
•	Made the shopping cart centered on the page instead of floating to the right.
•	Enhanced responsive design for mobile devices, adjusting product width and cart layout.
•	Footer styling updated with clear spacing and centered content.

7. JavaScript Updates
•	Added JavaScript for:
o	Dynamic product filtering.
o	Add to cart with login check.
o	Cart total calculation.
o	Remove items from cart.
o	Checkout functionality with login verification.
•	Fixed the issue with price formatting, ensuring all prices are calculated correctly even with commas in numbers.

8. SEO Improvements
•	Added JSON-LD schema markup for the store:
o	Includes business name, logo, website URL, address, phone, description, social media links, and opening hours.
•	Ensures search engines can understand your website and business.
•	Structured for easy extension to product-level schema in the future.

9. Miscellaneous Updates
•	Fixed modal behavior for login/sign-up:
o	Close button works correctly.
o	Clicking outside the modal closes it.
•	Added alerts for cart actions like adding items and checking out.
•	Standardized price parsing for local storage and cart calculation.

