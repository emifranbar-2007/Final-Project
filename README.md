# Proyecto Final: Sistema de Generación Multimodal - Ecosfera AI

**Estudiante:** Emiliano Franco Barbuto  
**Fecha:** Agosto 2026  
**Programa:** Introducción a la Inteligencia Artificial  

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

```

---

## 4. Registro de Activos Generados y Parámetros Técnicos

### Activos Visuales (Imágenes)

1. **Hero Banner - Bio-reactor:**
* **Prompt:** `A futuristic bio-reactor capsule generating green forest saplings inside a clean minimal laboratory, cinematic lighting, photorealistic, 8k resolution, shot on 35mm lens, corporate sustainability aesthetic`
* **Negative Prompt:** `blur, distortion, low quality, oversaturated, human hands`
* **Parámetros:** Aspect Ratio `16:9` | CFG Scale `7.5` | Seed `42819`
* **Muestra:**![Hero Banner](imagen1.png)



2. **Equipo de Investigación:**
* **Prompt:** `A diverse team of biogenetics researchers (latin american, asian, caucasian) inspecting a glowing plant seedling inside a modern greenhouse, soft natural sunlight, professional corporate photography`
* **Negative Prompt:** `extra limbs, deformed faces, unnatural skin texture, render`
* **Parámetros:** Aspect Ratio `16:9` | CFG Scale `7.0` | Seed `91823`
* **Muestra:**![Equipo de Investigacion](imagen2.png)



3. **Visualización de Impacto:**
* **Prompt:** `Aerial drone view of a lush restored rainforest merging seamlessly with a smart sustainable city, morning fog, golden hour lighting, hyperrealistic`
* **Negative Prompt:** `dystopian, smog, pollution, industrial chimneys`
* **Parámetros:** Aspect Ratio `16:9` | CFG Scale `8.0` | Seed `11029`
* **Muestra:**![Visualizacion de Impacto](imagen3.png)




### Activos Sonoros (Audio)

1. **Locución Comercial (15 seg):**
* **Guion:** *"En Ecosfera, no solo imaginamos un futuro verde: lo codificamos. Descubre la primera biotecnología capaz de acelerar la reforestación nativa."*
* **Parámetros:** Voz femenina institucional | Tono: Inspirador / Corporativo | Ritmo: 120 WPM | Estabilidad: 75% | Claridad: 85%.
* **Reproductor:**<audio controls src="audio1.mp3"></audio>


2. **Audio Logo (5 seg):**
* **Guion:** *"Ecosfera. Tecnología que echa raíces."*
* **Parámetros:** Voz masculina grave | Tono: Cálido | Efectos: Fondo ambiental sintético con frecuencia baja.
* **Reproductor:**<audio controls src="audio2.mp3"></audio>



---

## 5. Matriz de Ética y Responsabilidad en IA

| Dimensión | Riesgo Identificado | Plan de Mitigación / Corrección |
| --- | --- | --- |
| **Sesgos Visuales** | Tendencia del modelo a generar científicos exclusivamente masculinos/occidentales. | Se incluyeron explícitamente descriptores de diversidad étnica (`latin american, asian, caucasian`) en el prompt. |
| **Alucinaciones Visuales** | Deformación de extremidades o instrumentos de laboratorio irreales. | Uso de *Negative Prompts* estrictos (`extra limbs, deformed faces`) y control de *CFG Scale* en 7.0 - 8.0. |
| **Clonación de Voz / DDAA** | Riesgo de imitar sin autorización voces de figuras públicas reconocidas. | Creación de perfiles sintéticos originales configurando parámetros de voz propios. |
| **Derechos de Autor** | Uso de nombres de artistas o estilos protegidos en los prompts visuales. | Se utilizaron únicamente términos técnicos fotográficos (ej. `35mm lens, golden hour`) sin citar artistas vivos. |

---

## 6. Conclusiones

La implementación de este sistema demuestra que la IA generativa alcanza su máximo valor cuando se orquesta mediante **sistemas de prompts estructurados** y se audita con **criterios éticos claros**. El flujo de trabajo desarrollado es escalable, replicable y listo para su uso en entornos corporativos reales.

