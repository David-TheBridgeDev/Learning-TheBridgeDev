# Learning-TheBridgeDev 🚀

> **"Bridging the Gap between Engineering and AI"**

Este repositorio es el diario de aprendizaje técnico de un Ingeniero Senior. Su objetivo principal es documentar y explorar la intersección entre la ingeniería de software tradicional y el desarrollo asistido por Inteligencia Artificial.

---

## 🛠️ Automatización y Estándares

Para garantizar la calidad y consistencia de la documentación, este proyecto utiliza un flujo de trabajo automatizado para archivos Markdown:

- **[Prettier](https://prettier.io/)**: Gestiona el formato visual (ancho de línea, espaciado, estilo).
- **[Markdownlint](https://github.com/DavidAnson/markdownlint)**: Asegura la estructura semántica (jerarquía de títulos, listas, etc.).

### ⚡ Scripts Disponibles

Puedes ejecutar estos comandos desde la terminal:

- `npm install`: Instala todas las dependencias necesarias.
- `npm run fix`: Ejecuta el formateo y el linting en todo el proyecto.
- `npm run format`: Aplica solo los estilos visuales de Prettier.

> [!TIP]
> **Configuración en el IDE:** Si utilizas IntelliJ o WebStorm, hemos configurado un *File Watcher* que ejecuta estas correcciones automáticamente al presionar `Ctrl + S`.

---

## 📚 Estructura del Proyecto

- `/ai`: Documentación específica sobre modelos LLM, RAG y automatizaciones.
- `AGENTS.md`: Directrices críticas para asistentes de IA (Contexto, Estilo y Estándares).
- `GEMINI.md`: Guía de referencia rápida para el asistente del proyecto.

---

## ✍️ Guía de Contribución (AI-Assisted)

Este proyecto sigue reglas estrictas de redacción definidas en [AGENTS.md](./AGENTS.md):

1. **Dualidad de Valor:** Contenido útil tanto para principiantes como para ingenieros experimentados.
2. **Foco en el "Por Qué":** No solo documentamos comandos, sino la razón técnica detrás de cada decisión.
3. **Validación:** El código sugerido debe ser modular y seguir principios SOLID/Clean Code.

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](./LICENSE).
