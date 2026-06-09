# ☕ Proyecto: Café Noir - Menú Digital

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es desarrollar una interfaz web minimalista e integral para el menú de una cafetería de especialidad llamada "Café Noir". Visualmente implementa un estilo "dark" con acentos "pink/reddish". Técnicamente, el propósito principal es demostrar el dominio de flujos de trabajo colaborativos en Git, el manejo de ramas (*branching*), la gestión de Pull Requests y la resolución efectiva de conflictos de código.

## 👥 Integrantes y Roles (Simulados)
Para el desarrollo de esta práctica individual, se asumieron y emularon las responsabilidades de los siguientes roles de un equipo de desarrollo:
* **Líder de Proyecto:** Planificación del flujo de trabajo de Git, inicialización del repositorio y aprobación de Pull Requests.
* **Diseñador Web:** Definición de la hoja de estilos (`style.css`), paleta de colores corporativa y maquetación visual del menú.
* **Integrador / Desarrollador:** Implementación de la estructura del contenido (`index.html`) y responsable de la resolución de conflictos en la rama principal.
* **Documentador:** Redacción de este archivo técnico de documentación (`README.md`) y estructura de la presentación ejecutiva.

## 🔄 Flujo de Trabajo Usado (Git Flow Simplificado)
1.  **Estructura Base:** Se creó la rama `main` con la configuración inicial del proyecto.
2.  **Ramificación:** Se abrieron de forma paralela dos ramas de desarrollo: `dev` (para lógica y contenido) y `diseno` (para estilos e interfaz).
3.  **Simulación de Conflicto:** Ambos roles modificaron concurrentemente la etiqueta del título principal (`<h1>`) en sus respectivas ramas para forzar un escenario de colisión de código.
4.  **Pull Request:** Se procesó un Pull Request con revisión de código simulada para unificar la rama `dev`.
5.  **Resolución de Conflictos:** Se realizó un *merge* manual local para corregir las líneas en conflicto de la rama `diseno`, eligiendo una solución unificada y limpia antes del despliegue final en `main`.
