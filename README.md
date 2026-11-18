# 📄 Hoja de Vida en Formato ATS (Applicant Tracking System)

Plantilla y versión web de currículum profesional diseñada específicamente para cumplir con los estándares de lectura de los sistemas de seguimiento de candidatos (**ATS - Applicant Tracking Systems**), utilizados por plataformas como LinkedIn, Indeed, Workday, Lever y Greenhouse.

---

## 🎯 ¿Por qué el formato ATS?

Los sistemas ATS procesan y filtran automáticamente los currículums antes de que lleguen a manos de un reclutador humano. Las plantillas con diseños en múltiples columnas, tablas, gráficos complejos o imágenes suelen romper el analizador (*parser*), provocando el descarte automático de la postulación.

Esta versión resuelve ese problema mediante:
- **Estructura en una sola columna:** Flujo de lectura lineal y predecible.
- **HTML5 semántico:** Uso estricto de etiquetas estándar (`<header>`, `<main>`, `<section>`, `<article>`, `<address>`, `<ul>`, `<li>`).
- **Sin elementos que confundan al bot:** Libre de imágenes decorativas o capas superpuestas.
- **Palabras clave (*Keywords*):** Habilidades y tecnologías organizadas por categorías estándar de la industria tech.
- **Exportación perfecta a 1 página:** Reglas `@media print` optimizadas para generar un PDF de una sola hoja sin líneas huérfanas.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Marcado semántico y accesible.
* **CSS3:** Tipografía estándar de alta legibilidad (Arial / Helvetica), espaciado armónico y reglas de impresión para PDF.

---

## 📂 Estructura del Directorio

```text
Hoja de vida (ATS)/
├── css/
│   └── style.css       # Estilos globales y reglas de impresión (@media print)
├── img/                # Directorio sin elementos gráficos (exclusivo para estándares ATS)
├── index.html          # Estructura principal del currículum
└── README.md           # Documentación del proyecto
```

---

## 🚀 Cómo Visualizar y Exportar a PDF

1. **Abrir en navegador:** Haz doble clic en el archivo `index.html` o usa una extensión como *Live Server* en Visual Studio Code.
2. **Generar PDF de 1 página:**
   * Presiona `Ctrl + P` (en Windows) o `Cmd + P` (en Mac).
   * En **Destino**, selecciona **Guardar como PDF**.
   * En **Diseño**, selecciona **Vertical**.
   * En **Tamaño de papel**, selecciona **Carta (Letter)** o **A4**.
   * En **Márgenes**, selecciona **Predeterminados** o **Ninguno**.
   * Desmarca la opción *Encabezados y pies de página*.
   * Haz clic en **Guardar**.

---

## 👤 Autor

**Juan Diego Rodríguez Yanquen**
* 📍 Bogotá D.C., Colombia
* ✉️ [juandrodriguezy057@gmail.com](mailto:juandrodriguezy057@gmail.com)
* 💼 [LinkedIn](https://www.linkedin.com/in/juan-rodriguez-3b2589450)
* 💻 [GitHub](https://github.com/juandirodriguezy)
