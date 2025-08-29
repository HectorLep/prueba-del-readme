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

## 🚀 Cómo Empezar (Entorno de Desarrollo en Windows)

Esta guía detalla los pasos para configurar y ejecutar el proyecto en un entorno de desarrollo de Windows.

### Prerrequisitos

Asegúrate de tener instalado lo siguiente:

1.  **Git:** [Descargar e instalar desde git-scm.com](https://git-scm.com/downloads)
2.  **Node.js (v22.18 LTS):** [Descargar el instalador .msi para Windows](https://nodejs.org/en/download).
3.  **Nginx:**
    * [Descargar Nginx v1.28.0](https://nginx.org/download/nginx-1.28.0.zip) y descomprimirlo en una ubicación fácil de recordar (ej: `C:\nginx`).
4.  **pnpm:** Abre una terminal de **PowerShell como Administrador** y ejecuta el siguiente comando:
    ```powershell
    Invoke-WebRequest "[https://get.pnpm.io/install.ps1](https://get.pnpm.io/install.ps1)" -UseBasicParsing | Invoke-Expression
    ```

### Instalación y Ejecución

1.  **Clona el repositorio:** Abre una terminal (como Git Bash o PowerShell) en la carpeta donde quieras guardar el proyecto y ejecuta:
    ````bash
    git clone [https://github.com/tcurihual/AyunPet.git](https://github.com/tcurihual/AyunPet.git)
    cd AyunPet
    ````

2.  **Configura Nginx:** Este paso es crucial para que el backend y el frontend se comuniquen correctamente en tu entorno local.
    * Navega a la carpeta donde descomprimiste Nginx (ej: `C:\nginx`).
    * Entra en la carpeta `conf` y abre el archivo `nginx.conf` con un editor de texto.
    * Borra todo el contenido de ese archivo y reemplázalo con el contenido del archivo `nginx.conf` que se encuentra en la raíz de este repositorio.
    * Abre una terminal en la carpeta raíz de Nginx (ej: `C:\nginx`) y ejecuta los siguientes comandos para iniciar el servidor:
    ````bash
    # Verifica que la configuración es correcta
    nginx -t
    
    # Inicia Nginx (si ya estaba corriendo, recarga la configuración)
    start nginx
    nginx -s reload
    ````
    *Nota: `start nginx` solo necesita ejecutarse una vez. Para futuros cambios en la configuración, solo usa `nginx -s reload`.*

3.  **Configura las Variables de Entorno:**
    * En la raíz del proyecto, busca el archivo `.env.example`.
    * Crea una copia de este archivo y renómbrala a `.env`.
    * Rellena las variables necesarias (como las claves de Supabase) dentro del nuevo archivo `.env`.

4.  **Instala todas las dependencias:** `pnpm` leerá el `package.json` principal e instalará todo lo necesario para el backend y el frontend.
    ````bash
    pnpm install
    ````

5.  **¡Inicia el proyecto!** Este único comando levantará todo el ambiente de desarrollo web (backend y frontend).
    ````bash
    pnpm run dev:web
    ````

Después de unos momentos, la terminal te indicará las direcciones (ej: `localhost:5173`) donde la aplicación web estará corriendo.
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
