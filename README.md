# 📄 Hoja de Vida en Formato ATS &bull; Juan Diego Rodríguez Yanquen

Currículum profesional desarrollado en **HTML5 semántico y CSS3**, optimizado específicamente para cumplir con los estándares técnicos y de lectura de los sistemas de seguimiento de candidatos (**ATS - Applicant Tracking Systems**), como Workday, Greenhouse, Lever, Taleo y los analizadores automáticos de LinkedIn e Indeed.

[![HTML5](https://img.shields.io/badge/HTML5-Semántico_ATS-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Print_Engineering-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![ATS Compliant](https://img.shields.io/badge/ATS-100%25_Compliant-success?style=flat-square)](https://www.jobscan.co/blog/ats-resume/)
[![Page Size](https://img.shields.io/badge/Output-1_Página_Exacta-blue?style=flat-square)](#)

---

## 🎯 Fundamentos Técnicos del Estándar ATS

Los analizadores de CV automáticos procesan documentos mediante extracción de texto plano y mapeo de entidades de datos. Los diseños convencionales con múltiples columnas, tablas desordenadas, íconos incrustados o fotografías fragmentan el árbol del DOM, provocando la mezcla de información o el descarte automático de la postulación.

Esta implementación resuelve esas fricciones mediante principios técnicos estructurados:

* **Arquitectura Lineal en 1 Columna:** Flujo de lectura continuo (`top-to-bottom`) que garantiza la extracción secuencial de cada sección sin mezclar columnas.
* **HTML5 Semántico Estricto:** Uso de `<header>`, `<main>`, `<section>`, `<article>`, `<address>`, `<ul>` y `<li>` para definir con claridad la jerarquía entre datos de contacto, resumen, experiencia, educación y habilidades.
* **Optimización de Palabras Clave (*Keywords*):** Clasificación estandarizada de competencias tecnológicas (Lenguajes, Frontend, Backend, Bases de Datos y Herramientas) alineada a los filtros de búsqueda de reclutadores técnicos.
* **Tipografía de Compatibilidad Universal:** Uso de fuentes de sistema de alta legibilidad (`Arial`, `Helvetica`, `sans-serif`) que no dependen de recursos web externos para su renderizado.
* **Ingeniería de Impresión (`@media print`):** Reglas CSS calibradas (`@page`, `break-inside: avoid;`, ajuste de interlineado y paddings) que garantizan que el documento compile en **exactamente 1 página** sin desbordes huérfanos.

---

## 🛠️ Stack y Tecnologías

| Área | Tecnología | Implementación |
|---|---|---|
| **Estructura** | HTML5 Semántico | Jerarquización accesible (`<h1>`-`<h3>`, `<address>`, `<article>`) |
| **Estilos & Layout** | CSS3 Moderno | Flexbox para encabezados de experiencia, reseteo de márgenes |
| **Exportación** | `@media print` | Compresión armónica para salida limpia a formato PDF en tamaño Carta / A4 |

---

## 📂 Estructura del Directorio

```text
Hoja de vida (ATS)/
├── css/
│   └── style.css       # Estilos visuales y reglas avanzadas de impresión (@media print)
├── img/                # Directorio sin elementos gráficos (estricto cumplimiento ATS)
├── index.html          # Marcado semántico del currículum
└── README.md           # Documentación técnica del proyecto
```

---

## 👤 Contacto y Autor

**Juan Diego Rodríguez Yanquen**
* 📍 Bogotá D.C., Colombia
* ✉️ [juandrodriguezy057@gmail.com](mailto:juandrodriguezy057@gmail.com)
* 💬 WhatsApp: [+57 310 669 0137](https://wa.me/573106690137)
* 💼 [LinkedIn](https://www.linkedin.com/in/juan-rodriguez-3b2589450)
* 💻 [GitHub](https://github.com/juandirodriguezy)
