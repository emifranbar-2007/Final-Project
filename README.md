# Proyecto Final: Sistema de Generación Multimodal - Ecosfera AI

**Estudiante:** Emiliano Franco Barbuto  
**Fecha:** Agosto 2026  
**Programa:** Certificación en Introduccion a la Inteligencia Artificial   

---

## 1. Resumen Ejecutivo y Objetivos

### Contexto del Proyecto
El presente proyecto simula la consultoría técnica y creativa para **Ecosfera**, una empresa ficticia de biotecnología enfocada en la reforestación automatizada. El objetivo es construir un **Sistema de Producción de Prompts** capaz de orquestar la creación de activos visuales y sonoros estandarizados, garantizando coherencia de marca, eficiencia operativa y cumplimiento de estándares éticos.

### Objetivos Clave
1. Disminuir en un 70% el tiempo de conceptualización de campañas multimodales mediante prompts maestros.
2. Garantizar coherencia estética y sonora en los activos generados con IA.
3. Implementar una matriz de auditoría ética para mitigar sesgos y alucinaciones en los modelos generativos.

---

## 2. Cronograma de Ejecución

| Fase | Tarea | Estado |
| :--- | :--- | :--- |
| **Fase 1** | Definición de problema, alcance y System Prompt | Completado |
| **Fase 2** | Diseño del Prompt Maestro e ingeniería de instrucciones | Completado |
| **Fase 3** | Generación y parametrización de activos (3 imágenes, 2 audios) | Completado |
| **Fase 4** | Auditoría ética, detección de riesgos y mitigación | Completado |
| **Fase 5** | Compilación de documentación y publicación | Completado |

---

## 3. Arquitectura del Sistema de Prompts

### A. System Prompt (Instrucciones Base)
> *"Eres 'Aura', una Consultora Senior en Estrategia de IA Multimodal y Branding Sostenible. Tu rol es diseñar, supervisar y estructurar campañas de comunicación corporativa utilizando modelos de lenguaje, generación de imágenes y síntesis de voz. Tu tono es profesional, analítico, enfocado en la precisión técnica, el respeto a las normativas de propiedad intelectual y la eliminación de sesgos visuales/sonoros."*

### B. Prompt Maestro
```text
[ROL]: Director Creativo Multimodal con IA
[OBJETIVO]: Generar activos técnicos para la marca Ecosfera en el sector Biotecnología.
[ESTRUCTURA DE SALIDA]:
1. Prompt Visual: Estilo, iluminación, encuadre, parámetros (Seed, CFG Scale, AR) y Negative Prompt.
2. Prompt de Audio: Perfil de voz, tono, ritmo, pausas narrativas y efectos de ambiente.
3. Evaluación Ética: Identificación de posibles sesgos visuales o alucinaciones sonoras.
