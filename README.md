🛍️ IBM Front-End E-Commerce Product Page

A modern, responsive, and accessible E-Commerce Product Page built using IBM Design System principles.
This project showcases best practices in front-end architecture, modular component design, and IBM Carbon Design System integration for a professional enterprise-grade product interface.


---

🚀 Features

🧱 IBM Carbon Design System Integration – UI components styled and structured using IBM’s Carbon library.

⚡ Responsive Design – Optimized for mobile, tablet, and desktop breakpoints.

🛒 Dynamic Product Data – Fetches and displays product details dynamically from mock or live APIs.

💳 Add to Cart Functionality – Interactive cart and product quantity management.

🔍 Product Image Gallery – Zoom, thumbnails, and carousel support.

🌐 Internationalization (i18n) – Supports multiple locales for global users.

♿ Accessibility (WCAG 2.1) – Fully compliant with accessibility standards.

🧩 Reusable Components – Clean, modular architecture using React + Carbon.

🧠 IBM Brand Consistency – Typography, colors, and spacing align with IBM branding.



---

🏗️ Tech Stack

Layer	Technology

Framework	React 18+
UI Library	Carbon Design System (IBM)
Styling	SCSS / CSS Modules
State Management	Redux Toolkit / Context API
Routing	React Router DOM
API Handling	Axios / Fetch
Build Tool	Vite / Webpack
Testing	Jest + React Testing Library
Linting	ESLint + Prettier



---

📁 Project Structure

ibm-fe-ecommerce/
│
├── public/                # Static assets (images, favicon, etc.)
├── src/
│   ├── assets/            # Icons, fonts, product images
│   ├── components/        # Reusable UI components
│   │   ├── Header/
│   │   ├── ProductCard/
│   │   ├── ProductDetails/
│   │   └── Cart/
│   ├── pages/             # Page-level components (Home, ProductPage, Checkout)
│   ├── services/          # API calls and business logic
│   ├── store/             # Redux slices or context logic
│   ├── styles/            # Global styles, themes
│   ├── App.jsx            # Main app entry
│   └── main.jsx           # React root render
│
├── .env                   # Environment variables
├── .eslintrc.js           # Linting configuration
├── package.json
├── vite.config.js / webpack.config.js
└── README.md


---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/ibm-fe-ecommerce.git
cd ibm-fe-ecommerce

2️⃣ Install dependencies

npm install

3️⃣ Run the development server

npm run dev

4️⃣ Build for production

npm run build

5️⃣ Run tests

npm test


---

🧰 Environment Variables

Create a .env file in the root directory and include:

VITE_API_BASE_URL=https://api.example.com
VITE_ENV=development


---

🧩 Key Components

Component	Description

ProductCard	Displays product summary with image, title, and price.
ProductDetails	Shows detailed product info with image gallery, description, and cart actions.
CartDrawer	Slide-in panel for cart overview and checkout link.
Header	IBM-branded navigation bar with search and cart icons.
Footer	Contains brand info and helpful links.



---

🧪 Testing

Unit tests written using Jest and React Testing Library.

Run coverage:


npm run test:coverage


---

💡 Design Guidelines

This project follows:

IBM Carbon Design System

IBM Accessibility Guidelines

WCAG 2.1 AA Compliance



---

🧭 Future Enhancements

🔐 User authentication (login/signup)

💬 Reviews and ratings module

📦 Inventory management

🌈 Dark mode support

🧾 Checkout and payment integration



---

Author: Ajiba S
Gmail: ajibaajiba481@gmail.com
GitHub:(https://github.com/ajibaajiba481-ship-it/Ajiba.git)

📜 License

This project is licensed under the MIT License — see the LICENSE file for details.
