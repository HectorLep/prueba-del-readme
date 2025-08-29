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
