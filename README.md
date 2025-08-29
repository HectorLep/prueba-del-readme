<p align="center">
  <strong>🌍 Idiomas disponibles / Available Languages:</strong><br>
  <a href="README.md">🇪🇸 Español</a> |
  <a href="README.en.md">🇺🇸 English</a>
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=tcurihual.AyunPet&left_color=black&right_color=blue&style=for-the-badge&left_text=Visitas" alt="Visitas" />
  <img src="https://img.shields.io/github/stars/tcurihual/AyunPet?style=for-the-badge&logo=github&label=Estrellas"
       alt="GitHub Stars" />
  <img src="https://img.shields.io/github/forks/tcurihual/AyunPet?style=for-the-badge&logo=github&label=Forks"
       alt="GitHub Forks" />
  <img src="https://img.shields.io/github/issues/tcurihual/AyunPet?style=for-the-badge&label=Issues"
       alt="GitHub Issues" />
  <img src="https://img.shields.io/github/last-commit/tcurihual/AyunPet?style=for-the-badge&label=Último_Commit"
       alt="Último commit" />
  <img src="https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge"
       alt="Licencia" />
</p>

# 🐾 AyudPet 🐾

<p align="center">
  <img src="https://img.shields.io/badge/Estado-En_Desarrollo-orange?style=for-the-badge" alt="Estado del Proyecto">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
</p>

[![Logo de AyudPet](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)](https://github.com/HectorLep/prueba-del-readme/raw/main/assets/logo.png)
> Una plataforma web y aplicación móvil para centralizar y agilizar el proceso de adopción de mascotas.

---

## 📝 Descripción del Proyecto

**AyudPet** es una solución integral que incluye una plataforma web y una aplicación móvil, desarrollada para la asignatura `Taller de Integración II y IV` en la `Universidad Católica de Temuco`.

El proyecto busca optimizar el proceso de adopción de mascotas, conectando de forma eficiente a fundaciones y rescatistas con potenciales adoptantes. A través de nuestras plataformas, ofrecemos herramientas centralizadas para la gestión de animales, estandarizando la información y mejorando la visibilidad para aumentar la tasa de adopciones responsables.

---

## ✨ Características Principales

* **🐶 Gestión de Publicaciones (Para Fundaciones)**
    * Publica y administra perfiles de mascotas con información detallada (fotos, historia, salud).
    * Actualiza en tiempo real el estado de la adopción ("disponible", "en proceso", "adoptado").

* **🔍 Búsqueda y Adopción (Para Adoptantes)**
    * Busca y filtra mascotas por especie, tamaño, edad y más, tanto en la web como en la app.
    * Postula a una adopción a través de un formulario simple y seguro.
    * Guarda perfiles de mascotas en una lista de favoritos.

* **💬 Interacción y Comunidad**
    * Resuelve dudas a través de un sistema de comentarios en cada publicación.
    * Accede a perfiles transparentes de las organizaciones para generar confianza.

* **🛡️ Administración y Moderación**
    * Panel de control para que los administradores gestionen usuarios y contenido reportado, asegurando un entorno seguro.

---

## 🛠️ Tecnologías Utilizadas

* **Backend:** `Node.js` + `Express` + `TypeScript`
    * **Node.js:** Entorno para ejecutar JavaScript en el servidor.
    * **Express:** Framework para construir la API del backend.
    * **TypeScript:** Lenguaje con tipado estático para un código más robusto.

* **Frontend Web:** `Vite` + `React` + `TypeScript`
    * **React:** Librería para construir interfaces de usuario interactivas.
    * **Vite:** Herramienta de desarrollo rápida para construir y servir el proyecto.
    * **TypeScript:** Lenguaje con tipado estático para el desarrollo frontend.

* **Base de Datos:** `Supabase`
    * Plataforma que provee una base de datos relacional (PostgreSQL), autenticación y APIs auto-generadas.

* **Aplicación Móvil:** `Expo` + `React Native`
    * **React Native:** Framework para crear aplicaciones móviles nativas usando React.
    * **Expo:** Plataforma y herramientas que simplifican el desarrollo y la compilación de apps en React Native.

---

## 🚀 Cómo Empezar (Guía Rápida para Windows)

### Prerrequisitos

Asegúrate de tener instalado el siguiente software:
* [**Git**](https://git-scm.com/downloads)
* [**Node.js v22 LTS**](https://nodejs.org/en/download)
* [**Nginx**](https://nginx.org/download/nginx-1.28.0.zip)
* **pnpm:** (instalar desde PowerShell con `Invoke-WebRequest "https://get.pnpm.io/install.ps1" -UseBasicParsing | Invoke-Expression`)

### Instalación y Ejecución

1.  **Clonar el Repositorio:**
    ````bash
    git clone [https://github.com/tcurihual/AyunPet.git](https://github.com/tcurihual/AyunPet.git)
    cd AyunPet
    ````

2.  **Configurar y Ejecutar Nginx:**
    * Copia el contenido del archivo `nginx.conf` de este repositorio al archivo `conf/nginx.conf` de tu instalación de Nginx.
    * Desde la carpeta de Nginx, ejecuta en la terminal: `start nginx` y luego `nginx -s reload`.

3.  **Configurar el Entorno:**
    * Crea una copia del archivo `.env.example`, renómbrala a `.env` y añade tus claves (ej: Supabase).

4.  **Instalar Dependencias:**
    * En la raíz del proyecto, ejecuta el siguiente comando:
    ````bash
    pnpm install
    ````

5.  **Iniciar el Entorno de Desarrollo:**
    * Este único comando levantará el backend y el frontend web:
    ````bash
    pnpm run dev:web
    ````

La terminal te mostrará la URL donde la aplicación estará corriendo.
---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## 👤 Autores

* **Miguel Fernández** - [@kurovoxx](https://github.com/kurovoxx)
* **Héctor Lepio** - [@HectorLep](https://github.com/HectorLep)
* **Agustin Verga** - [@sonickiller39](https://github.com/sonickiller39)
* **Christopher Solis** - [@Insert-name-115](https://github.com/Insert-name-115)
* **Maximiliano Sáez** - [@Mxtsi7](https://github.com/Mxtsi7)
* **Benjamin Rojas** - [@pvcdf](https://github.com/pvcdf)
* **Diego Ortiz**
* **Sebastian Mena**
