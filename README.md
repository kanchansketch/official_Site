# Reinventing - Official Website

![Reinventing Logo](https://img.icons8.com/color/48/000000/mind-map.png)

## 🚀 About Reinventing
**Reinventing** is a forward-thinking tech company dedicated to transforming ideas into digital reality. We specialize in building scalable web applications, providing high-quality training, and delivering premium software solutions.

Our mission is to **reinvent** the way businesses and individuals interact with technology, ensuring modern, efficient, and aesthetically pleasing experiences.

---

## 🛠️ Tech Stack
This project is built using modern web standards to ensure performance, SEO, and maintainability:

-   **Frontend**: HTML5, CSS3 (Custom Glassmorphism Design), Vanilla JavaScript (ES6+).
-   **Backend / Auth**: [Supabase](https://supabase.com/) (Authentication & Storage).
-   **Security**: Row Level Security (RLS) & JWT Authentication (`anon` key).
-   **Deployment**: [Vercel](https://vercel.com/) (Global Edge Network).
-   **Version Control**: Git & GitHub.

---

## ✨ Features

### 1. Premium UI/UX
-   **Dark/Light Mode**: Fully responsive theme toggle with persistence.
-   **Glassmorphism**: Modern frosted glass effects on cards and navigation.
-   **Animations**: Smooth fade-in scroll effects and interactive hover states.

### 2. Services Showcase
-   **Web Development**: Custom sites and apps.
-   **Training & Internship**: Mentorship programs for aspiring developers.
-   **Consulting**: Technical guidance for startups.

### 3. Certificate Verification System
A secure system for issuing and validating internship/training certificates.

-   **Upload Portal (`/upload.html`)**:
    -   Admin-only access.
    -   Requires **Project API Key** for authentication.
    -   Uploads PDF certificates directly to Supabase Storage.
    -   Renames files to unique IDs (e.g., `CERT-001`).

-   **Public Verification (`/verify.html`)**:
    -   Publicly accessible.
    -   Users enter a Certificate ID.
    -   System instantly validates and displays the certificate status.

---

## ⚙️ How to Run Locally

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/kanchansketch/official_Site.git
    cd official_Site
    ```

2.  **Open in Browser**
    Simply open `index.html` in your preferred browser.
    *Recommended: Use "Live Server" extension in VS Code.*

3.  **Deploy**
    ```bash
    npx vercel --prod
    ```

---

## 🔐 Security Note
This project uses **Supabase Row Level Security (RLS)**.
-   **Uploads**: Restricted to authenticated users (using the provided API Key).
-   **Downloads/Views**: Publicly accessible via the Verification portal.

---

### © 2026 Reinventing Company. All rights reserved.
*Designed & Developed by Kanchan Kumar Sharma.*
