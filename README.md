<p align="center">
  <strong>🌍 Idiomas disponibles / Available Languages:</strong><br>
  <a href="README.md">🇪🇸 Español</a> |
  <a href="README.en.md">🇺🇸 English</a>
</p>

# 🐾 AyudPet 🐾

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

## 🚀 Cómo Empezar

Este proyecto utiliza una estructura de monorepo. Sigue estos pasos para ejecutarlo localmente.

### Prerrequisitos

* Node.js v22 (LTS)
* npm y Git
* Una cuenta de Supabase para obtener las claves de la API.
* La aplicación **Expo Go** en tu teléfono móvil para probar la app.

### Instalación y Ejecución

1.  **Clona el repositorio:**
    ````bash
    git clone [https://github.com/TU_USUARIO/ayudpet.git](https://github.com/TU_USUARIO/ayudpet.git)
    cd ayudpet
    ````

2.  **Inicia el Backend:**
    ````bash
    # En una terminal
    cd backend
    npm install
    cp .env.example .env  # Configura tus claves de Supabase aquí
    npm run dev
    ````

3.  **Inicia el Frontend Web:**
    ````bash
    # En una segunda terminal
    cd frontend-web
    npm install
    npm run dev
    ````

4.  **Inicia la Aplicación Móvil:**
    ````bash
    # En una tercera terminal
    cd mobile-app
    npm install
    npx expo start
    # Escanea el código QR con la app Expo Go en tu teléfono
    ````

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## 👤 Autores

* **Miguel Fernández**
* **Héctor Lepio** - [@HectorLep](https://github.com/HectorLep)
* **Agustin Verga**
* **Christopher Solis**
* **Maximiliano Sáez**
* **Benjamin Rojas**
* **Diego Ortiz**
* **Sebastian Mena**
