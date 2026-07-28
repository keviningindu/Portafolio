# 🚀 Portafolio Profesional de QA Automation, Python & Data Analysis

**Kevin Gudiño** *Ingeniero Industrial | Software QA Automation Engineer | Python Developer | Data Analyst* 📍 Zapopan, Jalisco, México  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-fabian-gudino)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/keviningindu)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kevin.ing.indu@gmail.com)

---

## 📌 Sobre Mí

Soy **Ingeniero Industrial** graduado y certificado como **Software QA Engineer por TripleTen**, especializado en la automatización de pruebas de software, análisis de datos y desarrollo en Python.

Mi enfoque combina la rigurosidad analítica de la ingeniería industrial con metodologías ágiles de desarrollo para garantizar la calidad, estabilidad e impacto de negocio en cada entregable. Cuento con experiencia práctica en validación de software (UI y API REST), desarrollo y publicación de aplicaciones móviles en producción (Google Play Store), y optimización de procesos operativos.

---

## 🛠️ Stack Tecnológico

| Categoría | Herramientas y Tecnologías |
| :--- | :--- |
| **QA & Testing** | Selenium WebDriver, Pytest, Postman, Jira, TestRail, Pruebas API REST, Pruebas Manuales, Casos de Prueba, Reportes de Defectos |
| **Lenguajes & Backend** | Python 3, SQL, REST APIs, JSON |
| **Análisis de Datos** | Pandas, NumPy, DataLyzer, Excel Avanzado |
| **Desarrollo & Herramientas** | Git, GitHub, VS Code, Google Play Console |
| **Metodologías** | Scrum, Kanban, ISTQB / QA Best Practices, ISO 9001 |

---

## 📁 Estructura del Repositorio y Proyectos Destacados

```
├── 📁 Urban_Scooter_QA/           # Proyecto Capstone: Pruebas de Software & Automatización (TripleTen)
├── 📁 DataLuck_AI_Dev/            # Desarrollo & QA de Aplicación Móvil de Análisis de Datos
├── 📁 DocuTalk_Audio_App/         # Desarrollo & Validación de Aplicación Móvil Text-to-Speech
└── 📁 Logistics_Data_Optimization/# Análisis de Datos y Control de Calidad Operativa
```

---

### 1. 🚲 Urban Scooter — QA Automation & API Testing (Proyecto Capstone)

- **¿Qué es este proyecto?:** Proyecto integrador de fin de certificación enfocado en la validación de calidad de punta a punta (End-to-End) para una plataforma web y backend de alquiler de patinetas eléctricas.
- **Producto bajo prueba:** API REST del servicio backend y flujos de usuario críticos en la interfaz web (registro de usuario, creación de pedidos, cálculo de tarifas y gestión de entregas).
- **Objetivo:** Verificar la integridad lógica, rendimiento de endpoints y estabilidad de la interfaz para reducir fallos críticos en producción.
- **Alcance:** Pruebas de API REST con Postman y automatización con Python/Pytest; pruebas de interfaz de usuario con Selenium WebDriver; diseño de matriz de casos de prueba y reporte de errores en Jira.
- **Artefactos incluidos:**
  - `test_cases_matrix.xlsx`: Matriz completa de pruebas manuales y cobertura de requerimientos.
  - `test_api_pytest.py`: Suite automatizada de pruebas para verificación de endpoints de la API.
  - `test_ui_selenium.py`: Scripts automatizados para la prueba del flujo de reserva frontend.
  - `bug_reports_jira.pdf`: Documentación estructurada de errores encontrados con severidad, pasos de reproducción y resultados esperados.
- **Decisiones clave de QA:**
  - Se priorizó la automatización del flujo de creación de pedidos por ser la función transaccional de mayor valor de negocio.
  - Se implementaron pruebas de límites (*Boundary Value Analysis*) y partición de equivalencia en las entradas de API para capturar errores de validación previa.
- **Resultados e Impacto:**
  - Cobertura superior al 85% en endpoints principales de la API.
  - Detección previa a lanzamiento de 12 defectos críticos en la API y UI.
  - Suite de regresión ejecutable en menos de 2 minutos.
- **Próximos Pasos:** Integrar la ejecución automatizada con GitHub Actions (CI/CD).

---

### 2. 📊 DataLuck AI — Desarrollo y QA de Aplicación Móvil

- **¿Qué es este proyecto?:** Aplicación móvil desarrollada en Python diseñada para el análisis ágil de datos y generación de métricas predictivas para usuarios finales.
- **Producto bajo prueba:** Arquitectura lógica backend, procesamiento de archivos de datos y flujo de experiencia de usuario en la app.
- **Objetivo:** Construir y lanzar una aplicación estable, ligera y precisa en el procesamiento de datos, cumpliendo con las normativas de publicación de tiendas móviles.
- **Alcance:** Desarrollo completo del motor analítico en Python, pruebas de rendimiento, validación de parámetros técnicos de configuración (`app.json`) y despliegue exitoso en Google Play Console.
- **Artefactos incluidos:**
  - `data_engine.py`: Módulos de procesamiento analítico y transformaciones de datos.
  - `app.json`: Configuración técnica de empaquetado y permisos.
  - `qa_release_checklist.md`: Matriz de verificación técnica previa al lanzamiento.
- **Decisiones clave:**
  - Estructuración modular del código para facilitar pruebas unitarias independientes de cada función matemática.
  - Ejecución de pruebas de estrés con conjuntos de datos de diferente tamaño y formato antes del empaquetado.
- **Resultados e Impacto:**
  - Aprobación y publicación oficial en Google Play Store.
  - 0 fallos críticos reportados en las primeras fases de uso activo.

---

### 3. 🎙️ DocuTalk — Aplicación Móvil de Conversión de Texto a Audio

- **¿Qué es este proyecto?:** Aplicación móvil diseñada para la lectura de documentos de texto y conversión en audio de alta fidelidad mediante síntesis de voz.
- **Producto bajo prueba:** Motor de lectura de archivos, procesamiento de fragmentos de texto y rendimiento de generación de audio.
- **Objetivo:** Garantizar la lectura fluida de documentos de gran tamaño sin degradación del rendimiento de memoria en dispositivos móviles.
- **Alcance:** Integración de APIs de síntesis de voz, pruebas de integración de archivos de diversos formatos (TXT, PDF) y optimización de experiencia de usuario.
- **Artefactos incluidos:**
  - `audio_reader_core.py`: Lógica principal de ingesta de texto y reproductor.
  - `test_audio_conversion.py`: Pruebas de integración para la API de conversión.
- **Decisiones clave:**
  - Implementación de procesamiento asíncrono para evitar el congelamiento de la interfaz durante la lectura de textos extensos.
- **Resultados e Impacto:**
  - Aplicación funcional publicada en la tienda de apps con excelente tiempo de respuesta.

---

### 4. 📈 Optimización de Datos Operativos y Gestión de Calidad

- **¿Qué es este proyecto?:** Proyectos de auditoría de procesos, análisis de datos y control de calidad aplicados a entornos de operación logística e industrial (Velagas, Arbomex DataLyzer).
- **Objetivo:** Transformar datos operativos desestructurados en tableros de control y automatizaciones para la toma de decisiones.
- **Herramientas:** Python, SQL, Excel Avanzado, DataLyzer, Metodologías ISO 9001.
- **Resultados e Impacto:**
  - Automatización de la generación de informes operativos, reduciendo el tiempo de preparación manual.
  - Estandarización de métricas de calidad en líneas de proceso.

---

## 📬 Contacto y Redes

- **LinkedIn:** [linkedin.com/in/kevin-fabian-gudino](https://www.linkedin.com/in/kevin-fabian-gudino)
- **GitHub:** [github.com/keviningindu](https://github.com/keviningindu)
- **Email:** [kevin.ing.indu@gmail.com](mailto:kevin.ing.indu@gmail.com)

---
*Este repositorio está estructurado siguiendo las mejores prácticas de documentación de QA y desarrollo software.*
