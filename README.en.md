<p align="center">
  <strong>🌍 Idiomas disponibles / Available Languages:</strong><br>
  <a href="README.md">🇪🇸 Español</a> |
  <a href="README.en.md">🇺🇸 English</a>
</p>

# 🐾 AyudPet 🐾

[![AyudPet Logo](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)
> A web platform and mobile application to centralize and streamline the pet adoption process.

---

## 📝 Project Description

**AyudPet** is a comprehensive solution that includes a web platform and a mobile application, developed for the `Integration Workshop II & IV` course at the `Universidad Católica de Temuco`.

The project aims to optimize the pet adoption process by efficiently connecting foundations and rescuers with potential adopters. Through our platforms, we offer centralized tools for managing animals, standardizing information, and improving visibility to increase the rate of responsible and successful adoptions.

---

## ✨ Main Features

* **🐶 Publication Management (For Foundations)**
    * Publish and manage pet profiles with detailed information (photos, history, health).
    * Update the adoption status in real-time ("available", "in process", "adopted").

* **🔍 Search and Adoption (For Adopters)**
    * Search and filter pets by species, size, age, and more, on both the web and the app.
    * Apply for adoption through a simple and secure online form.
    * Save pet profiles to a favorites list.

* **💬 Interaction and Community**
    * Resolve questions through a comment system on each publication.
    * Access transparent profiles of organizations to build trust.

* **🛡️ Administration and Moderation**
    * A control panel for administrators to manage users and reported content, ensuring a safe environment.

---

## 🛠️ Tech Stack

* **Backend:** `Node.js` + `Express` + `TypeScript`
    * **Node.js:** Server-side JavaScript runtime environment.
    * **Express:** Framework for building the backend API.
    * **TypeScript:** Statically typed language for more robust code.

* **Frontend Web:** `Vite` + `React` + `TypeScript`
    * **React:** Library for building interactive user interfaces.
    * **Vite:** Fast development tool for building and serving the project.
    * **TypeScript:** Statically typed language for frontend development.

* **Database:** `Supabase`
    * A platform that provides a relational database (PostgreSQL), authentication, and auto-generated APIs.

* **Mobile Application:** `Expo` + `React Native`
    * **React Native:** Framework for creating native mobile applications using React.
    * **Expo:** A platform and set of tools that simplify the development and building of React Native apps.

---

## 🚀 Getting Started (Quickstart Guide for Windows)

### Prerequisites

Ensure you have the following software installed:
* [**Git**](https://git-scm.com/downloads)
* [**Node.js v22 LTS**](https://nodejs.org/en/download)
* [**Nginx**](https://nginx.org/download/nginx-1.28.0.zip)
* **pnpm:** (install from PowerShell with `Invoke-WebRequest "https://get.pnpm.io/install.ps1" -UseBasicParsing | Invoke-Expression`)

### Installation and Setup

1.  **Clone the Repository:**
    ````bash
    git clone [https://github.com/tcurihual/AyunPet.git](https://github.com/tcurihual/AyunPet.git)
    cd AyunPet
    ````

2.  **Configure and Run Nginx:**
    * Copy the content from the `nginx.conf` file in this repository to the `conf/nginx.conf` file of your Nginx installation.
    * From the Nginx folder, run in your terminal: `start nginx` and then `nginx -s reload`.

3.  **Configure the Environment:**
    * Create a copy of the `.env.example` file, rename it to `.env`, and add your keys (e.g., Supabase).

4.  **Install Dependencies:**
    * In the project's root directory, run the following command:
    ````bash
    pnpm install
    ````

5.  **Start the Development Environment:**
    * This single command will launch the backend and the web frontend:
    ````bash
    pnpm run dev:web
    ````

The terminal will show you the URL where the application is running.
---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## 👤 Authors

* **Miguel Fernández** - [@kurovoxx](https://github.com/kurovoxx)
* **Héctor Lepio** - [@HectorLep](https://github.com/HectorLep)
* **Agustin Verga** - [@sonickiller39](https://github.com/sonickiller39)
* **Christopher Solis** - [@Insert-name-115](https://github.com/Insert-name-115)
* **Maximiliano Sáez** - [@Mxtsi7](https://github.com/Mxtsi7)
* **Benjamin Rojas** - [@pvcdf](https://github.com/pvcdf)
* **Diego Ortiz**
* **Sebastian Mena**
