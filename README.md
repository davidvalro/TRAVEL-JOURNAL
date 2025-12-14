# ✈️ TRAVEL JOURNAL

## 🗺️ Diario Interactivo de Viajes (React)

### 📝 Descripción del Proyecto

**TRAVEL JOURNAL** es una aplicación web dinámica, construida íntegramente con **React**, que funciona como un diario de viaje interactivo. El objetivo principal de este proyecto es simular el registro, la visualización y la organización de entradas de destinos visitados utilizando la inyección de datos dinámicos.

Este proyecto fue desarrollado como una práctica intensiva para fortalecer habilidades clave en el ecosistema React, como:
* Manejo y estructuración de **Componentes Funcionales**.
* Inyección y gestión de **Propiedades (Props)** para comunicar componentes.
* Renderización de listas a partir de datos externos (JSON/Array).

---

### 🌟 Estructura del Proyecto y Componentes Clave

El diseño del diario se basa en un conjunto de componentes modulares que consumen la data del archivo `data.js`.

| Componente | Responsabilidad | Props Recibidas |
| :--- | :--- | :--- |
| **App** | Contenedor principal. Mapea la data de `data.js` para generar las tarjetas de viaje. | - |
| **Header** | Componente de presentación fijo en la parte superior. | - |
| **Card** | Componente reutilizable. Renderiza los detalles de una única entrada de viaje. | `item` (Objeto con los detalles del destino) |

#### Detalles de Cada Entrada
Cada entrada de viaje (`Card`) muestra información esencial:
* País y ubicación específica
* Fechas de inicio y fin del viaje
* Descripción del destino
* Enlace directo a la ubicación en Google Maps

---

### 💻 Stack Tecnológico

El proyecto fue inicializado y desarrollado utilizando el siguiente stack tecnológico:

* **Framework Principal:** React
* **Lenguajes:** JavaScript, HTML5, CSS3
* **Herramientas:** Vite (Bundler/Servidor)
* **Gestor de Paquetes:** npm

---

### 🚀 Getting Started

Sigue estos sencillos pasos para instalar las dependencias y ejecutar el proyecto en tu máquina local.

#### 1. Instalación y Ejecución

Asegúrate de estar en el directorio raíz del proyecto (`TRAVEL JOURNAL`) y ejecuta los siguientes comandos en tu terminal:

```bash
npm install
npm start
# o npm run dev

### 👨‍💻 Nota del Desarrollador

Este ejercicio es fundamental para comprender el concepto de **Diseño Orientado a Componentes** en React. Al separar la lógica de presentación en el componente `Card` y utilizar la función `map()` en el componente `App`, se garantiza que la interfaz sea **escalable** y **fácil de mantener** al añadir nuevas entradas de viaje, demostrando un uso eficaz del **patrón de reutilización de componentes**.