# Square Eyes – HTML and CSS assignment

This project is part of the Frontend Development course and focuses on building a complete, responsive, and accessible website based on a provided Figma design. The website consists of multiple pages that together form a full user flow: browsing films, viewing details, adding items to the cart, entering payment information, and receiving a confirmation message.

All HTML and CSS were written manually and follow the Figma layout as closely as possible.

---

##  File Structure-




## Pages in the Project

###  01. index.html
The homepage with the main message “Connecting Film-Lovers” and a list of film categories.  
Includes navigation and footer.

### 02. films.html
Displays all films according to the Figma design.  
Each film is shown with its title and price in a simple list layout.

### 03. product.html
Shows detailed information about a selected film (The Batman).  
Includes title, description, price, and a button to add the film to the cart.

### 04. cart.html
Shows the content of the shopping cart.  
Includes the selected film, its price, and a button to proceed to payment.

### 05. payment.html
A payment form with the following fields:  
Name, Card Number, Expiry Date, and CVC.  
Includes a button to complete the purchase.

### 06. confirmation.html
A confirmation page that displays a success message after the purchase is completed.  
Includes a button to return to the homepage.

---

## Design & Layout

- The layout follows the Figma design exactly.
- Colors and variables are stored in `_variables.css`.
- A CSS reset is included in `_reset.css`.
- All page-specific styling is in `styles.css`.
- Flexbox is used for layout.
- The project is built mobile-first with simple media queries.

---

## Accessibility (WCAG)

The project follows basic WCAG principles:

- Semantic HTML structure (header, main, section, footer).
- Clear heading hierarchy (h1, h2).
- Sufficient color contrast between text and background.
- Labels for all form fields.
- Consistent navigation across all pages.
- Readable text sizes on both mobile and desktop.
- Links and buttons are clearly identifiable.

---

## Validation

### HTML Validation
All HTML files were checked using the W3C HTML Validator.  
Any issues found (such as missing alt attributes or structural errors) were corrected.

### CSS Validation
`styles.css` was checked using the W3C CSS Validator.  
Warnings were reviewed and fixed when necessary.

---

## Responsiveness

- Mobile-first approach.
- Layout scales up using flexbox.
- Text and elements adjust to different screen sizes.
- Navigation works on all devices.

---

## Technologies Used

- HTML5  
- CSS3  
- Flexbox  
- CSS Variables  
- Reset CSS  
- Figma as design reference

---

## Summary

This project is a complete implementation of the Square Eyes website based on the provided Figma design.  
All pages were built manually, validated, and structured according to the assignment requirements.  
The focus was on clean code, accessibility, and staying faithful to the design.



