Kit-Kat Cat Café --- Digital Ordering System
1. Project Overview
Project name: Kit-Kat Cat Café Digital Ordering System
Purpose: A browser-based ordering interface for a fictional cat
café. Customers can browse and search a menu, add items to a cart,
remove items, apply promotional discounts, review order totals, and
confirm an order.

2. Features
- Displays menu items with prices and available stock.
- Searches menu items by name.
- Adds items to the cart and decreases the displayed stock.
- Removes items from the cart and restores the displayed stock.
- Applies promotional codes:
  - FBLARULES --- 20% discount
  - 20GONE --- $2.00 discount
  - SUPERSECRETEMPLOYEEDISCOUNT123! --- 70% employee discount
    (demonstration code)
- Calculates a 6% tax after the discount.
- Shows an order summary before confirmation.
- Displays feedback messages for actions such as an empty-cart
  checkout or a confirmed order.
  
3. How to Run the Program
   
  
  1 . Save the complete source code as index.html.
  
  2. Open index.html in a modern web browser, such as Google Chrome or
   Microsoft Edge.

  3. Use the search box to find menu items.
     
  4. Select Add to add an available item to the cart.
     
  5. Select Remove to remove one unit of an item.
     
  6. Enter a promotional code and select Apply to test a discount.
   
  7. Select Checkout to review the order, then choose Confirm
   Order or Back to Order.


  
  4. Files Included

  index.html: Main application file. Contains the HTML structure, Tailwind CSS  configuration and classes, styling, menu data, and JavaScript functionality.

  README.md: Project documentation, run instructions, feature list, and external-resource attributions.

5. Technologies, Libraries, and External Resources
HTML
Used to define the page structure, menu area, cart, order totals, and
checkout summary modal.
JavaScript
Used for menu rendering and search, cart and stock updates,
promotional-code handling, tax and total calculations, feedback
messages, and checkout interactions. The JavaScript is included in the <script> section of index.html.

Tailwind CSS
The project loads Tailwind CSS using the CDN script:

https://cdn.tailwindcss.com

Tailwind utility classes are used for layout, spacing, typography,
colors, borders, and interactive states. The source code also defines a
custom Tailwind color palette for the café theme.

Attribution: Tailwind CSS, https://tailwindcss.com/\
License information:
https://github.com/tailwindlabs/tailwindcss/blob/main/LICENSE
Google Fonts --- Plus Jakarta Sans
The project loads the Plus Jakarta Sans typeface through Google
Fonts:

https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap

Attribution: Plus Jakarta Sans, available through Google Fonts,
https://fonts.google.com/\
Font information and license:
https://fonts.google.com/specimen/Plus+Jakarta+Sans

The project does not intentionally include any other third-party
JavaScript libraries or UI templates in the provided source file. The
browser's built-in HTML, CSS, and JavaScript capabilities are also used.
  
  6. Source Code and Development Assistance
The full source code is provided in index.html. It includes the page
markup, Tailwind configuration, menu and stock data, and the functions
that operate the ordering interface.

7. Credits and Attribution Summary
- Tailwind CSS: https://tailwindcss.com/
- Plus Jakarta Sans via Google Fonts:
  https://fonts.google.com/specimen/Plus+Jakarta+Sans
- AI development assistance: Used to generate the main application
  implementation, as described in Section 6.
- Project-specific menu data and explanatory comments:
  Supplied/written by the project creator.

