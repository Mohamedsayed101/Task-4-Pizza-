# 🍕 Pizza-on-Demand Website

**Developed by: Mohamed Sayed Omar El-sayed**  
**ITI Summer Training Project**

---

## 📘 Project Overview

This project is a multi-page pizza ordering website built using **HTML5** and **CSS3**. It allows users to:

- Navigate through different sections
- Fill out an order form
- Choose pizza crust and toppings
- Receive a confirmation message
- Contact the developer via a dedicated page

---

## 🌐 Live Preview

[🔗 Click to View the Live Project](https://mohamedsayed101.github.io/Task-4-Pizza-/)

---

## 📁 Project Structure

Task-Two-/
├── main.html             # Home page with intro and layout
├── makeOrder.html        # Pizza order form with user inputs
├── contact.html          # Contact page with developer info
├── thankyou.html         # Thank you/confirmation page after submitting order

├── CSS/                  # All styling files
│   ├── style.css         # Global/shared styles (header, form, buttons, etc.)
│   ├── contact.css       # Styling specific to the contact page
│   └── thankyou.css      # Styling for the thank-you page

├── images/               # All project images
│   ├── صورتى.jpg         # Developer’s photo
│   └── pizza-1.jpeg      # Pizza image for main section or decoration

└── script.js             # Optional JavaScript (validation, interactivity)


---

## 🧩 Page Breakdown

### 1. `main.html` (Homepage)

- Contains the main **site logo** and **navigation bar**
- Welcomes the user and describes the pizza service
- Displays an image and motivational quote
- Uses `header`, `main`, `blockquote`, and `footer`

### 2. `makeOrder.html` (Order Form)

- Includes a structured form:
  - Name, address, phone, email
  - Pizza crust (radio buttons)
  - Toppings (checkboxes)
  - Number of pizzas (number input)
- `submit` redirects to `thankyou.html`
- Uses `<fieldset>`, `<legend>`, and semantic sections

### 3. `thankyou.html`

- Displays a success message after form submission
- Includes a button to return to the main page
- Styled using `thankyou.css`

### 4. `contact.html`

- Shows personal developer contact info:
  - Name
  - Email (mailto)
  - Phone (tel)
  - Physical address
- Uses `<ul>`, `<a href="mailto:...">` and `<a href="tel:...">`

---

## 🎨 CSS Styling Overview

### ✅ Common Layout Features

| Feature             | Description                                   |
|---------------------|-----------------------------------------------|
| CSS Variables       | Declared in `:root` for easy color control    |
| Responsive Design   | `@media` queries for mobile screens           |
| Flexbox             | Used in headers, navbars, and containers      |
| Button Hover        | Transitions with `background-color` change   |
| Clean UI            | Rounded corners, shadows, spacing consistency |

### 🔑 Key Variables in `:root`

```css
:root {
  --main-color: #570606c6;
  --secondary-color: #a2a4bf;
  --text-color: #fff;
  --highlight-color: #e63946;
  --bg-box: bisque;
  --border-radius: 8px;
  --box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  --padding: 15px;
}

## 🧠 Layout Principles

| Section         | Description                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------|
| **Header**      | Sticky positioning with logo on the left and a navigation bar centered or aligned to the right. |
| **Form**        | Inputs are grouped using `<fieldset>` and labeled by `<legend>` for accessibility and clarity. |
| **Inputs**      | Uniform padding, consistent border-radius, and controlled width ensure a clean and readable layout. |
| **Buttons**     | Styled with smooth hover transitions and consistent padding, using CSS variables.              |
| **Media Queries** | Responsive design ensures labels and inputs adjust to stack vertically on smaller screens.    |


## 🛠 Technologies Used

| Technology   | Purpose                                      |
|--------------|----------------------------------------------|
| **HTML5**    | Structure, forms, and layout of the webpages |
| **CSS3**     | Styling, layout, and responsive design       |
| **JavaScript** | *(Optional)* For interactivity and enhancements |


## 🚀 How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Mohamedsayed101/Task-4-Pizza-.git

## 💬 Contact Developer

- 👤 **Mohamed Sayed Omar El-sayed**  
- 📧 **Email:** [ms3655@fayoum.edu.eg](mailto:ms3655@fayoum.edu.eg)  
- 📱 **Phone:** +20 123 456 7890  
- 📍 **Location:** Fayoum, Egypt


---

You can save this content as a file named `README.md` in your project root.

Would you like me to help you create a downloadable version or GitHub push-ready structure too?
  
