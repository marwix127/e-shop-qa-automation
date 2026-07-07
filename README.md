# 🚀 E2E Automation Framework para E-Commerce

## Visión General del Proyecto

Este repositorio aloja la suite de pruebas End-to-End (E2E) diseñada para asegurar la funcionalidad crítica de la plataforma de E-commerce.

El enfoque principal es la prevención de regresiones en el flujo de compra principal, asegurando una experiencia de usuario fluida y libre de errores críticos tras cada deployment.

---

## 🛠️ Stack Tecnológico de Testing

Este proyecto fue desarrollado utilizando las siguientes herramientas de automatización:

- **Framework:** Cypress (JavaScript)
- **Lenguaje:** JavaScript / TypeScript
- **Gestión de Dependencias:** Node.js / npm

---

## 🎯 Cobertura de Pruebas (Casos Críticos)

La suite de Cypress cubre los siguientes flujos críticos de negocio (El "Happy Path"):

1. **Navegación:** Validación de la carga correcta de la página principal y las categorías.

2. **Búsqueda:** Prueba de la funcionalidad de búsqueda de productos por nombre.

3. **Flujo de Compra (Core):**
   - Selección y adición de un producto al carrito.
   - Actualización de la cantidad en el carrito.
   - Eliminación de un producto del carrito.
   - Navegación al checkout y validación de la información de resumen.

4. **Validación de Formulario:** Prueba de los mensajes de error en los campos de formulario del checkout.

---

## ⚙️ Cómo Ejecutar las Pruebas

Sigue estos pasos para descargar y ejecutar la suite de automatización en tu entorno local:

### 1. Requisitos

Asegúrate de tener Node.js y npm instalados.

### 2. Instalación de Dependencias

Clona el repositorio e instala las dependencias de Cypress:

```bash
git clone https://github.com/tu-usuario/e-shop-qa-automation.git
cd e-shop-qa-automation
npm install
```

### 3. Ejecución de la Suite

Para abrir la interfaz interactiva de Cypress y seleccionar la prueba:

```bash
npx cypress open
```

Para ejecutar todos los tests en modo headless (terminal):

```bash
npx cypress run
```

---

## 📈 Impacto y Estrategia de QA

- **Metodología:** Aplicación de pruebas de Regresión Funcional para garantizar la fiabilidad del flujo de negocio más importante de la aplicación.

- **Valor Añadido:** Reducción del tiempo de testing manual de X horas a una ejecución automatizada de Y segundos

- **Debugging:** Uso de la funcionalidad de Time Travel Debugging de Cypress para simplificar la identificación y reporte de defectos.
