# 🤖 AI Agency Landing Page

## Overview
This project is a visually polished, modern landing page for a fictional AI Agency. It focuses on demonstrating professional frontend development and UI/UX skills, including seamless **dark/light theme functionality** and secure external API integration.

## Key Features
* **Modern Frontend Stack:** Built with **React.js** and styled using **Tailwind CSS**.
* **Advanced UI/UX:** Utilizes **Framer Motion** for subtle, high-quality animations, enhancing user experience.
* **Secure Contact Form:** Features a functional contact form integrated with the **Web3Forms API**. The API key is securely managed via Vercel Environment Variables, demonstrating best practices for handling secrets.
* **User Feedback:** Uses **React Hot Toast** for success and error notifications on form submission.
* **Theming:** Includes a fully functional dark/light theme toggle.

## 🛠 Technology Stack
* **Framework:** React.js
* **Styling:** Tailwind CSS
* **Animation:** Framer Motion
* **Notifications:** React Hot Toast
* **Deployment:** Vercel

## ⚙️ Local Installation and Setup

**Prerequisites:** Node.js (LTS recommended)

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL Here]
    cd ai-agency-site
    ```
2.  **Install dependencies:**
    ```bash
    npm install 
    ```
3.  **Set up Environment Variables:** Create a file named `.env` in the root of the project and add your API key:
    ```
    VITE_WEB3FORMS_KEY="your-key-here"
    ```
4.  **Run the development server:**
    ```bash
    npm run dev
    ```