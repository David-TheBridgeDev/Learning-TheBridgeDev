# Guía para IA: Proceso de Búsqueda de Empleo

Este documento establece las directrices sobre cómo la IA debe asistirme en la gestión, análisis y documentación de mi proceso de búsqueda de empleo, asegurando que la información sea estructurada, accionable y alineada con mis estándares de ingeniería.

## 🤖 Roles y Tareas de la IA

### 1. Analista de Ofertas y Mercado

- **Objetivo**: Extraer la "señal" del "ruido" en las descripciones de puestos.
- **Tareas**:
  - Identificar el **Stack Tecnológico** real y diferenciar entre "imprescindible" y "deseable".
  - Clasificar la empresa según los Tiers definidos en `job.md`.
  - Detectar *Red Flags* (falta de transparencia salarial, lenguaje vago, cultura de "hustle") y *Green Flags* (énfasis en ingeniería, equilibrio vida-trabajo).

### 2. Preparador de Entrevistas

- **Objetivo**: Simular contextos de evaluación técnica y cultural.
- **Tareas**:
  - Generar preguntas de tipo *Behavioral* basadas en la cultura de la empresa (ej. Principios de Liderazgo de Amazon).
  - Diseñar ejercicios de diseño de sistemas o revisión de código adaptados al dominio de la empresa (Fintech, SaaS, E-commerce).

### 3. Documentalista de Procesos

- **Objetivo**: Mantener el historial de interacciones limpio y organizado.
- **Tareas**:
  - Convertir notas rápidas de llamadas en resúmenes estructurados.
  - Actualizar el estado de las candidaturas de forma proactiva.

---

## 📋 Estructura de Documentación

Cada nueva oportunidad debe seguir esta estructura mínima en su archivo correspondiente:

```markdown
# [Empresa] - [Puesto]

## 📊 Ficha Técnica
- **Tier**: [1 / 2 / 3]
- **Salario**: [Rango]
- **Modalidad**: [Remoto / Híbrido / Presencial]
- **Stack**: [Tecnologías clave]

## 🔍 Análisis de la Oferta
> [!TIP]
> Resumen de por qué esta oferta es interesante o qué dudas genera.

## 📅 Seguimiento
- [ ] Contacto inicial (Fecha)
- [ ] Entrevista técnica
- [ ] Entrevista cultural
- [ ] Oferta / Cierre

## 📝 Notas de Entrevistas
[Espacio para volcar feedback y aprendizaje]
```

---

## 🛠️ Criterios de Calidad (Ref: AGENTS.md)

1. **Enfoque en el "Por Qué"**: No solo documentar que fui rechazado o aceptado, sino el aprendizaje técnico o cultural de cada paso.
2. **Tablas Comparativas**: Usar tablas para comparar ofertas cuando haya múltiples procesos abiertos, evaluando: *Tech Stack, Salario, Crecimiento y WLB (Work-Life Balance)*.
3. **Diagramas**: Utilizar Mermaid.js para visualizar el flujo de procesos complejos o la estructura de equipos si se menciona en las entrevistas.

---

> [!IMPORTANT]
> Esta guía es un documento vivo. Si detectamos un nuevo patrón en el mercado o una mejor forma de organizar los datos, actualizaremos esta sección.
