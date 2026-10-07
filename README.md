# N9 Restaurant Web App 🍽️

A modern, responsive web application and local management system for **N9 Restaurant** — a fictional restaurant concept designed for testing and development. The project features full support for Arabic and English languages, real-time cart handling, client ordering, and an administrative control panel.

---

## 🎨 Brand & Identity
* **Restaurant Name:** N9 Restaurant *(Note: This is a fictional restaurant and brand name created purely for demonstration and portfolio purposes).*
* **Slogan:** "Authentic Flavors, Modern Experience." / "النكهة الأصيلة، بتجربة عصرية فريدة."

---

## 🚀 Features & Pages

1. **Home Page (`index.html`):**
   * Engaging welcome hero section with quick navigation links to the menu and order system.
   * Four-card core values section.
   * Brand story and vision overview.

2. **Menu Page (`menu.html`):**
   * Displays 8 test menu items with unified pricing.
   * Lazy-loading image optimization for smooth scrolling performance.

3. **Order Page (`order.html`):**
   * Interactive dish selection and cart management.
   * Customer checkout form supporting name, phone number, branch selection, order type, and special notes.
   * Country code selection and order confirmation step.

4. **Admin Dashboard (`admin.html`):**
   * Secure login gateway to review, update status, or delete incoming customer orders.
   * Server-side secure password verification (`ADMIN_PASSWORD`).

5. **Careers / Jobs Page (`jobs.html`):**
   * Call-to-action for submitting resumes via email or Instagram.

6. **404 Error Page (`404.html`):**
   * Fallback page for broken links with a quick return button to the homepage.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic markup and structure.
* **CSS3:** Modern styling, dark/light mode support, responsive layouts, and full RTL/LTR language direction handling inside `style.css`.
* **JavaScript:** Client-side interactivity, cart persistence, theme toggling, and translations (`ar.js`, `en.js`, `main.js`).
* **Node.js (Express / MJS):** Backend server and REST API managing customer orders stored locally in `data/orders.json` (`server.mjs`).

---

## ⚙️ Installation & Local Setup

To run this project locally on your machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/n9-restaurant.git](https://github.com/your-username/n9-restaurant.git)
   cd n9-restaurant
