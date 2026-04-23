# Learning-TheBridgeDev 🚀

> **"Bridging the Gap between Engineering and AI"**

Este repositorio es el diario de aprendizaje técnico de un Ingeniero Senior. Su
objetivo principal es documentar y explorar la intersección entre la ingeniería
de software tradicional y el desarrollo asistido por Inteligencia Artificial.

---

## 🛠️ Automatización y Estándares

Para garantizar la calidad y consistencia de la documentación, este proyecto
utiliza un flujo de trabajo automatizado para archivos Markdown:

- **[Prettier](https://prettier.io/)**: Gestiona el formato visual (ancho de
  línea, espaciado, estilo).
- **[Markdownlint](https://github.com/DavidAnson/markdownlint)**: Asegura la
  estructura semántica (jerarquía de títulos, listas, etc.).

### ⚡ Scripts Disponibles

Puedes ejecutar estos comandos desde la terminal:

- `npm install`: Instala todas las dependencias necesarias.
- `npm run fix`: Ejecuta el formateo y el linting en todo el proyecto.
- `npm run format`: Aplica solo los estilos visuales de Prettier.

> [!TIP] **Configuración en el IDE:** Si utilizas IntelliJ o WebStorm, hemos
> configurado un _File Watcher_ que ejecuta estas correcciones automáticamente
> al presionar `Ctrl + S`.

---

## 📚 Estructura del Proyecto

- `/AI`: Documentación específica sobre modelos LLM, RAG y automatizaciones.
- `/Software Engineering`: Guías de referencia para desarrollo Back-end,
  Front-end y Movilidad.
- `AGENTS.md`: Directrices críticas para asistentes de IA (Contexto, Estilo y
  Estándares).
- `GEMINI.md`: Guía de referencia rápida para el asistente del proyecto.

## 📖 Guías Técnicas

| Categoría                   | Recurso                                                        | Descripción                                                            |
| :-------------------------- | :------------------------------------------------------------- | :--------------------------------------------------------------------- |
| **Inteligencia Artificial** | [Enterprise AI Blueprint](AI/blueprint-for-enterprise-ai.md)   | Hoja de ruta estratégica para implementar IA en entornos corporativos. |
| **Inteligencia Artificial** | [Glosario de IA](AI/glossary.md)                               | Conceptos fundamentales: RAG, Agentes, HITL y más.                     |
| **Inteligencia Artificial** | [Transformer Architecture](AI/transformer-architecture.md)     | Análisis profundo de la arquitectura que revolucionó el NLP.           |
| **Back-end**                | [Java Guide](./Software%20Engineering/back-end/JAVA.md)        | Ecosistema Java, arquitectura JVM y Modern Java (Java 8+).             |
| **Front-end**               | [Angular Guide](./Software%20Engineering/front-end/ANGULAR.md) | Desarrollo empresarial con Angular, Signals y Standalone Components.   |
| **Mobility**                | [Flutter Guide](./Software%20Engineering/mobility/FLUTTER.md)  | Desarrollo multiplataforma nativo mediante composición de Widgets.     |

---

## ✍️ Guía de Contribución (AI-Assisted)

Este proyecto sigue reglas estrictas de redacción definidas en
[GEMINI.md](./GEMINI.md):

1. **Dualidad de Valor:** Contenido útil tanto para principiantes como para
   ingenieros experimentados.
2. **Foco en el "Por Qué":** No solo documentamos comandos, sino la razón
   técnica detrás de cada decisión.
3. **Validación:** El código sugerido debe ser modular y seguir principios
   SOLID/Clean Code.

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](./LICENSE).
