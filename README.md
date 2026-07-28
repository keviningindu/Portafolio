👋 Hola, soy Kevin Gudiño
Soy Ingeniero Industrial especializado en QA Automation, Desarrollo Python y Análisis de Datos. En este repositorio encontrarás evidencia de mi trabajo validando calidad de software, automatizando procesos y desarrollando aplicaciones, combinando rigor industrial con metodologías ágiles IT.

Navegación Rápida (Empieza Aquí):
●	📁 /Urban_Scooter_QA: Automatización de pruebas y QA manual para plataforma de alquiler.
●	📁 /DataLuck_AI_Dev: Desarrollo y validación de app analítica publicada en tiendas.
●	📁 /Logistics_Data_Analysis: Dashboards y optimización de datos (Datalyzer).

2. Proyecto 1: Urban Scooter (QA Automation)
●	¿Qué es esto?: Proyecto final de certificación enfocado en pruebas integrales y automatizadas de una plataforma de alquiler de scooters.
●	Producto / Funcionalidad bajo prueba: API del backend y flujos críticos de la interfaz de usuario para el registro y reserva de scooters.
●	Objetivo: Asegurar la calidad del flujo principal de reserva y verificar la correcta respuesta de los endpoints críticos.
●	Alcance: Pruebas de API, diseño de casos de prueba manuales (Jira) y automatización UI/API (Python, Selenium, Pytest).
●	Artefactos en esta carpeta:
○	test_cases.csv: Matriz de pruebas manuales y escenarios.
○	api_automation_pytest.py: Scripts de automatización de endpoints.
○	ui_selenium_tests.py: Automatización del flujo de reserva frontend.
○	bug_reports.pdf: Informe de defectos y riesgos documentados.
●	Decisiones clave: Prioricé el flujo de reserva ya que es la funcionalidad de negocio más crítica. Automaticé las pruebas de regresión en la API para optimizar validaciones futuras.
●	Resultados: Cobertura robusta en los endpoints críticos; scripts de automatización estables; reporte de bugs accionable para el equipo de desarrollo.
●	¿Qué mejoraría después?: Implementar integración continua (CI) para correr las pruebas automáticamente en cada confirmación de código.

3. Proyecto 2: DataLuck AI (Mobile App Data Analysis)
●	¿Qué es esto?: Aplicación móvil lanzada para el análisis rápido de datos usando algoritmos de Python.
●	Producto / Funcionalidad bajo prueba: Rendimiento del procesamiento de datos, estabilidad de la app y resolución de requerimientos de consola.
●	Objetivo: Ofrecer una herramienta analítica estable, fluida y validada bajo los estándares de publicación.
●	Alcance: Desarrollo backend, diseño UX, validación de parámetros técnicos y superación de QA comercial.
●	Artefactos en esta carpeta:
○	data_models.py: Algoritmos de análisis de datos e ingesta.
○	app_config.json: Configuración estructural y de despliegue.
○	release_notes.txt: Documentación de pruebas y resolución de requerimientos para publicación.
●	Decisiones clave: Opté por una arquitectura modular en Python para facilitar el testeo y mantenimiento. Validé exhaustivamente los requisitos previos a la publicación para garantizar la aprobación inmediata.
●	Resultados: Aplicación validada, aprobada y lanzada con éxito a los usuarios finales.
●	¿Qué mejoraría después?: Agregar dashboards integrados de métricas de rendimiento y expandir las pruebas unitarias para funciones predictivas.
