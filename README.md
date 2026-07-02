Amicart Bookstore
This is a simple e-commerce website for an online bookstore, made as a project for Sourcecode Lab. It's a front-end only project built using HTML, CSS and JavaScript.
About
Amicart is a basic online bookstore where users can browse books by category, search and filter books, add books to a cart, view/remove items from the cart, and log in to their account. The cart data is stored in the browser using localStorage, so it stays saved even if you refresh the page.
Pages
index.html - Home page with categories, featured books, testimonials, newsletter signup, contact form and FAQs
books.html - Books listing page with a search bar to filter books by title/author, and an "Add to Cart" button on each book
cart.html - Cart page showing all added books, with options to remove a single item or clear the whole cart
login.html - Login page with username/password fields, show/hide password, remember me checkbox and social login buttons
Signup page is linked in the navbar but not built yet.
Tech Used
HTML
CSS
JavaScript (localStorage for cart)
How to Run
Just download or clone this repo and open `index.html` in your browser. No installation or setup needed.
```
git clone https://github.com/your-username/amicart-bookstore.git
```
Login Details (for testing)
Username: admin
Password: 1234

How the Cart Works
Clicking "Add to Cart" on the books page saves the book name to localStorage
The cart page reads from localStorage and lists all added books
You can remove individual items or clear the entire cart
Cart data stays even after closing the browser (until cleared)
Things to Add Later
Real book images instead of placeholders
Quantity and price for each book, with a proper total

Signup page
Connect to a backend for real login/authentication and product data
Better cart handling (currently just stores book titles, not full book details)
Note
This project was made for learning purposes as part of Sourcecode Lab. Some features (like social login buttons) are just for UI and don't actually work yet.
