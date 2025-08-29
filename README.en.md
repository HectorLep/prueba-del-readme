<p align="center">
  <strong>🌍 Idiomas disponibles / Available Languages:</strong><br>
  <a href="README.md">🇪🇸 Español</a> |
  <a href="README.en.md">🇺🇸 English</a>
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=tcurihual.AyunPet&left_color=black&right_color=blue&style=for-the-badge" alt="Visitors" />
  <img src="https://img.shields.io/github/stars/tcurihual/AyunPet?style=for-the-badge&logo=github"
       alt="GitHub Stars" />
  <img src="https://img.shields.io/github/forks/tcurihual/AyunPet?style=for-the-badge&logo=github"
       alt="GitHub Forks" />
  <img src="https://img.shields.io/github/issues/tcurihual/AyunPet?style=for-the-badge"
       alt="GitHub Issues" />
  <img src="https://img.shields.io/github/last-commit/tcurihual/AyunPet?style=for-the-badge"
       alt="Last commit" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"
       alt="License" />
</p>

# 🐾 AyudPet 🐾

<p align="center">
  <img src="https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge" alt="Project Status">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
</p>

[![AyudPet Logo](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)
> A web platform and mobile application to centralize and streamline the pet adoption process.

---

## 📋 Table of Contents

- [📝 Project Description](#-project-description)
- [✨ Main Features](#-main-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started (Quickstart Guide for Windows)](#-getting-started-quickstart-guide-for-windows)
- [🤝 How to Contribute](#-how-to-contribute)
- [🆘 Support](#-support)
- [📜 License](#-license)
- [👤 Authors](#-authors)

---

## 📝 Project Description

**AyudPet** is a comprehensive solution that includes a web platform and a mobile application, developed for the `Integration Workshop II & IV` course at the `Universidad Católica de Temuco`.

The project aims to optimize the pet adoption process by efficiently connecting foundations and rescuers with potential adopters. Through our platforms, we offer centralized tools for managing animals, standardizing information, and improving visibility to increase the rate of responsible and successful adoptions.

---

## ✨ Main Features

### 🏢 For Foundations and Rescuers
**Centralized tools for efficient management.**
- ✅ **Simple Publishing:** Create and manage pet profiles with all the necessary information.
- ✅ **Real-Time Status Management:** Update if a pet is "available," "in process," or already "adopted."

### 🔍 For Future Adopters
**Find your ideal companion safely and with all the information you need.**
- ✅ **Advanced Search and Filters:** Filter by species, size, age, and more to find the perfect pet.
- ✅ **Secure Application Process:** Submit adoption requests through a standardized form.
- ✅ **Favorites List:** Save the profiles you are interested in so you don't lose track of them.

### 🛡️ For Administrators
**A safe and well-moderated environment for everyone.**
- ✅ **Control Panel:** Manage users and reported content.
- ✅ **Content Moderation:** Ensure that all publications comply with community standards.

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

## 🤝 How to Contribute

Contributions are welcome! This is a collaborative university project. If you want to help, please follow these steps:
1.  Look for an open `issue` on the [Issues](https://github.com/tcurihual/AyunPet/issues) tab or propose a new enhancement.
2.  For major changes, please open an `issue` first to discuss what you would like to change.
3.  Ensure you follow the project's style guides and standards.

---

## 🆘 Support

If you find a problem or have a suggestion, please use the official repository channels:

- **🐛 Report a Bug:** Open a new `Issue` [here](https://github.com/tcurihual/AyunPet/issues/new). Please be as detailed as possible.
- **💡 Suggest an Enhancement:** Start a `Discussion` [here](https://github.com/tcurihual/AyunPet/discussions) to propose new ideas or features.

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
