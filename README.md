# NexusSec - Static Web Deployment Project 🛡️

Este repositorio contiene el código fuente de **NexusSec**, una *Single Page Application* (SPA) de una firma ficticia de ciberseguridad y Ethical Hacking. 

El objetivo principal de este proyecto no es comercial, sino servir como un **entorno de laboratorio** realista y visualmente atractivo para prácticas de despliegue de infraestructura en la nube.

## 🚀 Objetivo del Proyecto

- Prácticas de alojamiento de sitios web estáticos.
- Laboratorios de despliegue en **Microsoft Azure (Blob Storage)**.
- Pruebas de configuración de dominios personalizados (Custom Domains) y CDN.

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica de la página.
- **CSS3:** Diseño responsivo, Dark Mode UI y animaciones (sin frameworks externos).
- **JavaScript (Vanilla):** Interactividad básica del frontend y simulación de envío de formularios.

## ⚙️ Cómo utilizar este repositorio

### Despliegue Local
Simplemente clona este repositorio y abre el archivo `index.html` en cualquier navegador web moderno. No requiere instalación de dependencias ni servidores locales.

### Despliegue en Azure Blob Storage (Sitio Estático)
1. Crea una **Storage Account** en tu portal de Azure.
2. Habilita la opción de **Static website** en la configuración.
3. Define `index.html` como tu documento de inicio (Index document name).
4. Sube el contenido de este repositorio al contenedor `$web` que Azure crea automáticamente.
5. Accede al sitio a través del **Primary endpoint** proporcionado por Azure.

---
*Desarrollado con fines educativos y de práctica cloud.*
