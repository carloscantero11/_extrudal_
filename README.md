# 📌 Extrudal

## 📑 Tabla de Contenido
- [Descripción](#-descripción)
- [Enlace en Línea](#-enlace-en-línea)
- [Características](#-características-técnicas)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación y uso](#ℹ️-instalación-y-uso)
- [Imágenes](#%EF%B8%8F-imágenes)
- [Problemas](#problemas)
- [Licencia](#-licencia)
- [Autores](#%EF%B8%8F-autores)

## 📜 Descripción

Es el sitio web oficial de [Extrudal C.A.](https://extrudal.com) con su catálogo digital de los perfiles de aluminio. Permite conocer a la empresa mediante su página de inicio, navegar por el catálogo, ver subcatálogos y productos, y contactar al equipo mediante formularios.

## 🌐 Enlace en Línea

🔗 [Click aquí para ver la página web](https://extrudal.com)

## 🎯 Características Técnicas

### **Inicio**
- **Homepage moderna** - Diseño atractivo orientado a conversión.
- **Responsive** - Adaptable a todos los dispositivos con Tailwind CSS.
- **Animaciones** - Microinteracciones fluidas con Framer Motion.
- **Rutas dinámicas** - URLs semánticas por categoría (`/catalogo/[productos]`).
- **Productos estáticos** - Datos desde JSON en `data/[productos].json`.
- **Iconos modernos** - Lucide React para visual consistencia.

### **Desarrollo**
- **Rendimiento** - Turbopack para desarrollo ultrarrápido.
- **TypeScript** - Código tipado, limpio y mantenible.
- **Arquitectura limpia** - Componentes modulares y buenas prácticas Next.js 16.

### **Next.js 16 con App Router**
- Server Components por defecto. Lectura asíncrona de archivos con Node.js `fs/promises`.
- Rutas dinámicas en tiempo real. Sin rebuild, lee JSON del filesystem bajo demanda.
- Protección contra caracteres maliciosos en URLs.
- Metadata dinámica para SEO automatizado.

### **Estructura de Datos**
- **Sin base de datos** - Sistema 100% estático basado en JSON.
- Array en app/catalogo/page.tsx con nombre, slug e imagen.
- `data/[productos].json` - JSONs independientes por cada producto.
- **Tipado completo** - Interfaces TypeScript para Data, Item y props de componentes.

### **Developer Experience**
- **Turbopack** - Bundler en Rust para builds casi instantáneos.
- **TypeScript strict mode** - Validación exhaustiva de tipos.
- **Hot Module Replacement** - Actualización en caliente durante desarrollo.
- **Componentes modulares** - Sistema de componentes reutilizables en `/components`.

## 💻 Tecnologías Utilizadas

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/) &nbsp;
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://reactjs.org/) &nbsp;
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) &nbsp;
[![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/) &nbsp;
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) &nbsp;
[![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)](https://pnpm.io/es/) &nbsp;
[![JSON Badge](https://img.shields.io/badge/JSON-000?logo=json&logoColor=fff&style=for-the-badge)](https://www.json.org/json-en.html) &nbsp;
[![Lucide Badge](https://img.shields.io/badge/Lucide-F56565?logo=lucide&logoColor=fff&style=for-the-badge)](https://lucide.dev/guide/react/) &nbsp;
[![Resend Badge](https://img.shields.io/badge/Resend-000?logo=resend&logoColor=fff&style=for-the-badge)](https://resend.com/) &nbsp;


## ℹ️ Instalación y uso

<br/>

>[!IMPORTANT]
> **Este repositorio solo contiene la documentación.**  
> **El código fuente es privado.** [Contáctame](https://karmadev.vercel.app/) para más información.

<br/>

## 🖼️ Imágenes

<div align="center">
<img width="1366" height="9905" alt="Extrudal_Home" src="https://github.com/user-attachments/assets/e855461c-9bbe-4602-9564-27c5ffeeeb8a" />
</div>


## ❗Problemas
Si tienes un problema, regístralo aquí o déjame un comentario. Asegúrate de primero revisar la consola de desarrollador de tu explorador para ver si puedes identificar el problema.

## 📝 Licencia

Este proyecto está licenciado bajo la [Extrudal C.A.](https://extrudal.com)

## 🖋️ Autores

- [Carlos Cantero](https://github.com/carloscantero11)
- [José Castro](https://github.com/JdanielCr07)


