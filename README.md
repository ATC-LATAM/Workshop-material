# Workshop Abre tu Ciencia — Material

Respaldo local de todo el material disponible en el **Workshop Abre tu Ciencia (ATC26)**, un taller de tres días para fortalecer capacidades y herramientas en ciencia abierta y reproducibilidad con referentes nacionales e internacionales.

**21, 22 y 23 de enero de 2026** · Pontificia Universidad Católica de Chile

🔗 **[Acceder al material oficial en atc26.com](https://atc26.com/)**

---

## D0 — PreWorkshop

*Miércoles 21 de enero — 18:30–21:00 (online)*

### PreWorkshop: Introducción a Positron

| | |
|---|---|
| **Presentador** | José Daniel Conejeros (Investigador Joven, Escuela de Gobierno & College UC) |
| **Resumen** | Taller introductorio para configurar el entorno de trabajo en R y familiarizarse con RStudio y Positron IDE. Revisión de funciones básicas y ejecución de scripts simples para garantizar que todos cuenten con las herramientas necesarias antes de los laboratorios posteriores. |
| **Material** | `D0/intro_positron_atc26/` |

---

## D1 — Día 1: Teoría y fundamentos de la Ciencia Abierta

*Jueves 22 de enero — Edificio Interdisciplinario, Sala Magíster, Escuela de Gobierno UC*

### Conferencias magistrales

| Sesión | Presentador | Resumen |
|--------|-------------|---------|
| **Perspectivas globales sobre reproducibilidad y transparencia** | Soledad Quiroz Valenzuela (Data Observatory) | Vicepresidenta de INGSA. Exposición sobre la importancia de la reproducibilidad y la transparencia en la investigación científica a nivel global. |
| **Protocolos y buenas prácticas para códigos y datos abiertos** | Juan Carlos Castillo (UChile) | Profesor Titular de Sociología. Fundamentos y prácticas para compartir código y datos de forma abierta y reproducible. |

**Material:** `D1/01_Presentaciones/`

### Panel

| Sesión | Panelistas | Resumen |
|--------|------------|---------|
| **Dimensiones éticas e institucionales de la Ciencia Abierta** | Macarena Rojas-Ábalos (ACHIPEC), Juan Alberto Lecaros (UDD), Catherine Reyes-Housholder (UC Chile) | Discusión sobre los dilemas éticos, institucionales y políticos asociados a la producción y circulación del conocimiento abierto. |

**Material:** `D1/02_Panel/`

### Laboratorios

| Laboratorio | Presentador | Resumen |
|-------------|-------------|---------|
| **1. Pre-registros y reportes en Open Science Framework** | Magdalena Gatsch (UC & UDD Chile) | Fundamentos y pasos del prerregistro. Con orientación de facilitadores, redactar y subir un prerregistro para un proyecto propio (por ejemplo, en OSF), especificando hipótesis, variables y análisis previstos. |
| **2. Flujo de trabajo reproducible con R y {targets}** | José Daniel Conejeros (UC Chile) | Estructurar análisis usando {targets}, creando flujos automatizados y transparentes que facilitan la actualización de resultados y el intercambio de código de forma reproducible. |
| **3. Documentos dinámicos con Quarto** | Stephanie Orellana (Cienciambiental) | Generar informes y manuscritos reproducibles con Quarto. Integrar narrativa, código y resultados en un único documento dinámico listo para compartir o enviar. |

| Material | Carpeta |
|----------|---------|
| Lab 1 | `D1/03_Laboratorios/01_Pre-registros/` |
| Lab 2 | `D1/03_Laboratorios/02_Targets/wks_targets_atc26/` |
| Lab 3 | `D1/03_Laboratorios/03_Quarto/taller_quarto_atc2026/` |

---

## D2 — Día 2: Herramientas para flujos de trabajo reproducibles

*Viernes 23 de enero — Sala San Andrés, College UC*

### Conferencias magistrales

| Sesión | Presentador | Resumen |
|--------|-------------|---------|
| **Protocolos y mejores prácticas para código y datos abiertos** | Juan David Leongomez (Universidad del Bosque, Colombia) | Profesor Asociado de Psicología. Estándares y protocolos para código y datos abiertos. Data Editor de Proceedings B (2026–2028). |
| **Diseño de repositorios de datos abiertos y estándares de metadatos** | Marcela Rivera (Bibliotecas UC) | Subdirectora de Recursos de Información. Infraestructura, repositorios institucionales y estándares FAIR para datos de investigación. |
| **El papel de la IA en la reproducibilidad científica: ventajas y retos** | Patricia Chandía (Caja Los Andes) | Analista de Gobierno de Datos. Cómo la IA puede favorecer o complicar la reproducibilidad y transparencia en la investigación. |

**Material:** `D2/01_Presentaciones/`

### Panel

| Sesión | Panelistas | Resumen |
|--------|------------|---------|
| **Experiencias en la implementación de flujos de trabajo reproducibles** | Estela Blanco (UC Chile), Sandra Flores (UChile), Riva Quiroga (OLS) | Investigadores de diferentes disciplinas comparten sus experiencias prácticas con flujos reproducibles en ciencia, salud pública y datos. |

**Material:** `D2/02_Panel/`

### Laboratorios

| Laboratorio | Presentador | Resumen |
|-------------|-------------|---------|
| **4. Control de versiones y repositorios en Git y GitHub** | Riva Quiroga (OLS) | Crear un repositorio abierto (GitHub o similar) para su proyecto, cargar código inicial y conjuntos de datos, y preparar metadatos básicos para garantizar accesibilidad y reproducibilidad. |
| **5. IA para la reproducibilidad: Cursor y otros agentes para código** | José Daniel Conejeros (UC Chile) | Explorar cómo herramientas de IA (Cursor, Positron Assistant, LM Studio) pueden favorecer la reproducibilidad mejorando la claridad del código, automatizando la documentación y sugiriendo mejoras en el flujo de trabajo, debatiendo retos éticos y prácticos. |

| Material | Carpeta |
|----------|---------|
| Lab 4 | *(Git/GitHub — material en línea)* |
| Lab 5 | `D2/03_Laboratorios/wks_iaca_atc26/` |

### Conferencia de cierre

| Sesión | Presentador | Resumen |
|--------|-------------|---------|
| **Reproducibilidad con Impacto: Cómo la Ciencia Abierta Puede Cambiar el Mundo** | Lars Vilhuber (Cornell University) | Profesor de Economía y Data Editor de la American Economic Association. Conferencia internacional sobre el impacto de la ciencia abierta en la credibilidad y sostenibilidad de la investigación empírica a nivel global. |

**Material:** `D2/04_Internacional/`

---

## Requisitos generales

- **R** (versión 4.0 o superior)
- **Quarto** (para reportes y presentaciones)
- **LaTeX** (opcional, para generar PDFs)

Cada laboratorio puede tener dependencias adicionales; consulta el `README` dentro de cada carpeta.

---

## Créditos

- **Workshop**: [Abre tu Ciencia](https://atc26.com/)
- **Financiamiento**: The Berkeley Initiative for Transparency in the Social Sciences (BITSS), managed by the Center for Effective Global Action (CEGA)
- **Licencia**: CC BY-SA 4.0

---

*Este repositorio es un respaldo local del material del workshop. Para la versión oficial y actualizada, visita [atc26.com](https://atc26.com/).*
