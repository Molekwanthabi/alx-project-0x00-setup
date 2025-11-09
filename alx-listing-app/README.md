Here’s a complete, ready-to-use **`README.md`** for your **ALX Listing App (Airbnb Clone)** project that meets **all the requirements** for your milestone task ✅

---

### 🏠 **README.md**

# ALX Listing App

## 📘 Project Overview

**ALX Listing App** is the foundation of an Airbnb-style property listing platform.
This project marks the starting point for building a **modern, responsive property listing web app** using **Next.js**, **TypeScript**, and **Tailwind CSS**.

The objective of this milestone is to scaffold the app with the correct project structure, reusable components, and essential configurations that will support future development.

---

## 🚀 **Project Setup**

### 1️⃣ Create the Project

Run the following command to create the app with all required settings:

```bash
npx create-next-app@latest alx-listing-app --typescript --tailwind --eslint --no-app-router --no-src-dir
```

### 2️⃣ Confirm Tailwind CSS Configuration

Your `tailwind.config.js` should contain:

```js
module.exports = {
  content: [
    './pages/**/*.{ts,tsx}',
    './components/**/*.{js,ts,jsx,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

In `styles/globals.css`, keep only the Tailwind base imports:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 🗂️ **Project Structure**

```
alx-listing-app/
├── components/
│   └── common/
│       ├── Button.tsx       # Reusable button component (e.g., “Book Now”, “Details”)
│       └── Card.tsx         # Reusable card component for property listings
│
├── constants/
│   └── index.ts             # Store reusable data, API URLs, and configuration strings
│
├── interfaces/
│   └── index.ts             # Contains TypeScript interfaces (CardProps, ButtonProps, etc.)
│
├── pages/
│   └── index.tsx            # Main landing page of the application
│
├── public/
│   └── assets/              # Folder for images, icons, and SVGs
│
├── styles/
│   └── globals.css          # Tailwind base, components, and utilities imports
│
├── README.md
└── package.json
```

---

## 🧱 **Folder Purpose**

| Folder / File          | Description                                                    |
| ---------------------- | -------------------------------------------------------------- |
| **components/common/** | Contains reusable UI components such as Cards and Buttons      |
| **interfaces/**        | TypeScript interface definitions for props and data models     |
| **constants/**         | Centralized constants for app-wide values (e.g., URLs, labels) |
| **public/assets/**     | Static assets such as images, icons, and SVGs                  |
| **pages/**             | Contains Next.js routes (starting with `index.tsx`)            |

---

## 🧩 **Tech Stack**

* **Next.js** – React framework for building fast, scalable web apps
* **TypeScript** – Enforces type safety and maintainability
* **Tailwind CSS** – Utility-first framework for styling and responsive layouts
* **ESLint** – Ensures consistent code style and quality

---

## 🧰 **Getting Started Locally**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/alx-listing-app.git
cd alx-listing-app
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Development Server

```bash
npm run dev
```

### 4️⃣ Open the App

Visit 👉 **[http://localhost:3000](http://localhost:3000)** to view the app running locally.

---

## ✅ **Verification Checklist**

* [x] Next.js app runs with no errors
* [x] TypeScript and ESLint are configured
* [x] TailwindCSS integrated successfully
* [x] Components (`Card`, `Button`) created under `components/common/`
* [x] Interfaces defined in `interfaces/index.ts`
* [x] Constants file set up in `constants/index.ts`
* [x] Assets added under `public/assets/`
* [x] README.md created with setup instructions

---

## 👨‍💻 **Author**

**Your Name**
Built as part of the **ALX Frontend Intermediate Projects** — *Airbnb Clone (Listing Page Foundation)*

> #ALX_SE #ALX_FE #ALX_PDFE #NextJS #TailwindCSS

---

Would you like me to also generate **starter code** for your `components/common/Button.tsx` and `Card.tsx` files (TypeScript + Tailwind ready)? It’ll help you get the app running immediately.
