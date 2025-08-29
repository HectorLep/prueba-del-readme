<p align="center">
  <strong>🌍 Idiomas disponibles / Available Languages:</strong><br>
  <a href="README.md">🇪🇸 Español</a> |
  <a href="README.en.md">🇺🇸 English</a>
</p>

# 🐾 AyudPet 🐾

[![Banner o Screenshot Principal de la App](https://via.placeholder.com/800x400.png?text=Plataforma+AyudPet+Web+%26+Móvil)](https://via.placeholder.com/800x400.png?text=Plataforma+AyudPet+Web+%26+Móvil)
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
* **Base de Datos:** `PostgreSQL` + `Prisma` (ORM)
* **Frontend Web:** `Vite` + `React` + `TypeScript`
* **Aplicación Móvil:** `React Native` + `TypeScript`

---

## 🚀 Cómo Empezar

Este proyecto utiliza una estructura de monorepo. Sigue estos pasos para ejecutarlo localmente.

### Prerrequisitos

* Node.js v22 (LTS)
* npm y Git
* Una instancia de PostgreSQL
* Entorno de desarrollo para React Native (JDK, Android Studio / Xcode)

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
    cp .env.example .env  # Configura tu base de datos aquí
    npx prisma migrate dev
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
    npx react-native run-android  # o run-ios
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
