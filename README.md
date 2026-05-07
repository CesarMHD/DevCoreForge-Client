# DevCoreForge - Client 🖥️

**DevCoreForge** es mi mesa de trabajo personalizada y centro de mando. Este proyecto nace de la necesidad de centralizar, organizar y documentar cada etapa de mis desarrollos. No es solo un gestor de proyectos, es una **bitácora técnica** para asegurar que cada solución implementada quede registrada para el futuro.

> ⚠️ **Estado del Proyecto:** En fase de arquitectura de módulos y diseño de interfaces.

---

## 🛠️ Stack Tecnológico

*   **Framework:** Angular (v19+)
*   **Lenguaje:** TypeScript (Tipado estricto)
*   **Estilos:** Tailwind CSS
*   **Estado:** RxJS / Signals
*   **Comunicación:** HttpClient con Interceptors para gestión de tokens JWT.

---

## ✨ Funcionalidades Principales

- **Gestor de Mesa de Trabajo:** Registro detallado de proyectos incluyendo propósito, descripción técnica, stack de tecnologías y materiales necesarios.
- **Bitácora de Procesos (Knowledge Base):** Organización de proyectos por etapas "paso a paso". Permite documentar comandos, configuraciones de archivos y notas técnicas de cada proceso para facilitar su reutilización en futuros desarrollos.
- **Banco de Ideas:** Espacio dedicado para capturar conceptos de proyectos futuros y funcionalidades pendientes de implementar.
- **Módulo de Decisiones Dinámicas:** Sistema para ayudar a la priorización de tareas. Incluye mecánicas como la "Ruleta de Proyectos" y filtros de prioridad para decidir qué empezar a construir hoy.
- **Acceso Directo:** Vinculación rápida a repositorios y URLs de producción de cada proyecto gestionado.

---

## 🔌 Conexión con el Backend

Este cliente consume de forma desacoplada la **DevCoreForge API** desarrollada en Laravel.
> [Repositorio API](https://github.com/CesarMHD/DevCoreForge-API.git)

---

## ⚙️ Configuración e Instalación

1. **Clonar el proyecto:**
   ```bash
   git clone https://github.com/CesarMHD/devcoreforge-client.git
2. **Instalar dependencias:**
   ```bash
   npm install
3. **Ejecutar en desarrollo:**
   ```bash
   ng serve
