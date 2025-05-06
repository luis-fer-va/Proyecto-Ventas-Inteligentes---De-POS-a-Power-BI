# Proyecto-Ventas-Inteligentes-De-POS-a-Power-BI

Bienvenidos al repositorio del proyecto retail donde mostraremos paso a paso cómo extraer datos desde un punto de venta, insertarlos en una base de datos usando el gestor SQL Server, transformarlos y finalmente visualizarlos en Power BI.  
Este proyecto tiene como objetivo demostrar un flujo completo de análisis de datos aplicado al sector retail, desde la extracción de datos desde un punto de venta (POS), su integración en una base de datos relacional, transformación, modelado y visualización utilizando herramientas modernas de análisis.

---

## 🛒 Descripción

**Ventas Inteligentes** simula el proceso real de captura, almacenamiento y análisis de datos de un supermercado.  
Los datos provienen de un software POS (punto de venta), almacenados inicialmente en una base de datos SQLite en una carpeta compartida de Dropbox.  
Luego son cargados y transformados en SQL Server, y finalmente utilizados para construir dashboards interactivos en Power BI orientados a la toma de decisiones.

---

## 🔧 Tecnologías y herramientas utilizadas

- **SQLite**: Base de datos original del punto de venta.  
- **Dropbox**: Medio de sincronización para recibir los datos localmente.  
- **SQL Server**: Base de datos de almacenamiento central y procesamiento.  
- **Power BI**: Herramienta de visualización y análisis.  
- **Python**: Automatización del proceso de carga de datos.  
- **Git & GitHub**: Control de versiones y documentación del proyecto.

---

## 🧩 Estructura del Proyecto

```plaintext
ventas-inteligentes-pos-powerbi/
├── data/
│   └── base_datos_pos.sqlite
├── src/
│   └── scripts_etl/
│       ├── extraccion.py
│       ├── transformacion.sql
│       └── carga.sql
├── docs/
│   ├── arquitectura.png
│   ├── linaje_datos.md
│   └── modelo_datos.pbix
├── sql_server/
│   └── scripts_creacion_tablas.sql
├── README.md
└── LICENSE

---

## 📈 Objetivos del Proyecto

- Simular la captura de datos desde un entorno POS real.  
- Cargar y estructurar los datos en un sistema robusto (SQL Server).  
- Diseñar la arquitectura de datos y el linaje de los mismos.  
- Transformar los datos en vistas analíticas listas para su uso en Power BI.  
- Crear reportes interactivos que permitan responder preguntas de negocio clave.

---

## ✅ Resultados Esperados

- Dashboard funcional en Power BI.  
- Repositorio completamente documentado y estructurado.  
- Demostración clara de habilidades en ingeniería de datos, modelado y análisis.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
