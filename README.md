<img width="1739" height="925" alt="image" src="https://github.com/user-attachments/assets/e193e4ed-f2f8-4088-a89b-2b69d67ecfb1" />







# 🏠 Airbnb Business Intelligence Dashboard

## 📌 Resumen Ejecutivo
Este proyecto forma parte de un trabajo **grupal** desarrollado en el contexto académico, simulando el funcionamiento del **departamento de Business Intelligence de una startup data‑driven** especializada en el sector inmobiliario.

El objetivo principal es demostrar nuestra capacidad para **transformar datos brutos de Airbnb en información accionable**, utilizando exclusivamente herramientas nativas de **Microsoft Power BI**, y presentarla mediante dashboards claros, interactivos y orientados a la toma de decisiones.

El proyecto se desarrolla como una prueba conceptual para un cliente ficticio (Airbnb), con el fin de analizar precios, disponibilidad y características de las propiedades en distintas ciudades.

---

## 🎯 Objetivos del Proyecto

- Cargar y transformar datos CSV de Airbnb mediante **Power Query**
- Modelar los datos siguiendo un enfoque **multidimensional (hechos y dimensiones)**
- Crear **medidas DAX** para análisis descriptivo y comparativo
- Diseñar un **dashboard interactivo y profesional** en Power BI
- Extraer **insights de negocio accionables**
- Documentar el proceso de forma clara y reproducible

---

## ❓ Preguntas de Negocio
El dashboard está diseñado para responder, entre otras, a las siguientes preguntas:

- ¿Cómo se distribuyen los precios de las propiedades por ciudad y barrio?
- ¿Qué tipos de propiedad son más comunes y cuáles generan mayor ingreso potencial?
- ¿Existen patrones temporales en la disponibilidad?
- ¿Qué zonas presentan mayor concentración de propiedades?
- ¿Qué diferencias clave existen entre ciudades (benchmarking)?

---

## 📊 Dataset

- **Fuente**: Datos públicos de Airbnb proporcionados en formato CSV
- **Ciudades analizadas**:
  - Madrid
  - Londres
  - Milán
  - Nueva York
  - Tokio
  - Sídney

- **Estructura general de los datos**:
  - Identificador de la propiedad
  - Precio por noche
  - Tipo de propiedad y habitación
  - Disponibilidad
  - Ubicación (ciudad, barrio, coordenadas)
  - Atributos y características adicionales

> ⚠️ Todos los archivos CSV han sido integrados y transformados **exclusivamente mediante Power Query**, sin uso de herramientas externas.

---

## 🏗️ Arquitectura de la Solución

La solución sigue una arquitectura clásica de BI:

1. **ETL – Power Query**
   - Carga de archivos CSV
   - Limpieza de valores nulos y duplicados
   - Tipado correcto de columnas
   - Transformaciones y columnas calculadas

2. **Modelo de Datos**
   - Separación entre tablas de hechos y dimensiones
   - Relaciones definidas y documentadas
   - (Si aplica) tabla de calendario

3. **Capa Analítica – DAX**
   - Medidas básicas (totales, promedios, conteos)
   - Medidas de análisis comparativo

4. **Visualización – Power BI**
   - Dashboards interactivos
   - Filtros globales (slicers)
   - Navegación entre páginas

---

## 📈 Dashboard

El proyecto se materializa en un **único archivo de Power BI**, que centraliza todo el proceso de carga, modelado, análisis y visualización:

📂 **`/powerbi/Proyecto.pbix`**

### Estado actual del dashboard

El dashboard actualmente incluye:

- Visualizaciones de **distribución de precios** por ciudad
- Comparativa de precios entre ciudades
- Análisis de propiedades por tipo de alojamiento
- Mapas con la localización de las propiedades
- Filtros interactivos por ciudad y tipo de propiedad

El diseño está orientado a un **análisis descriptivo y comparativo**, permitiendo identificar diferencias relevantes entre mercados inmobiliarios internacionales.

---

## 💡 Principales Insights

A partir del análisis actual realizado en el dashboard, se pueden extraer los siguientes insights:

- Existen **diferencias significativas de precios medios** entre ciudades, siendo Nueva York y Londres las más caras de media.
- El **tipo de propiedad** influye de forma clara en el rango de precios, especialmente entre viviendas completas y habitaciones privadas.
- Algunas ciudades presentan una **alta concentración de propiedades** en zonas muy concretas, visibles en los mapas.
- La distribución de precios muestra una **asimetría clara**, con presencia de outliers en todas las ciudades analizadas.

Estos insights permiten realizar comparativas entre mercados y sirven como base para futuras ampliaciones del análisis.

---

## ▶️ Instrucciones de Uso

1. Clonar o descargar este repositorio
2. Abrir el archivo `.pbix` con **Power BI Desktop**
3. Si es necesario, actualizar las rutas de los CSV
4. Refrescar los datos
5. Navegar por las distintas páginas del dashboard usando filtros y botones

---

## 👥 Equipo de Trabajo

Proyecto desarrollado de forma **colaborativa**.

| Miembro | Responsabilidades |
|--------|------------------|
| Miembro 1 | ETL y Power Query |
| Miembro 2 | Modelo de datos y DAX |
| Miembro 3 | Visualizaciones y UX |
| Miembro 4 | Insights y documentación |

*(Los roles pueden solaparse según la contribución real del equipo)*

---

## 🗂️ Estructura del Repositorio

```
/airbnb-bi-project
│
├── powerbi/
│   └── airbnb_dashboard.pbix
│
├── docs/
│   ├── etl.md
│   ├── modelo-datos.md
│   ├── medidas-dax.md
│   └── insights.md
│
├── images/
│   └── dashboard_overview.png
│
└── README.md
```

---

## 📌 Gestión del Proyecto

- Metodología: Kanban
- Herramienta: *(Trello / Jira / GitHub Projects – especificar)*

---

## 🚀 Estado del Proyecto

✔️ Carga y unificación de múltiples fuentes CSV
✔️ Limpieza y transformación de datos en Power Query
✔️ Modelo de datos funcional para análisis comparativo
✔️ Medidas DAX básicas implementadas
✔️ Dashboard interactivo operativo

🟡 Documentación técnica en desarrollo
🟡 Posible ampliación a análisis temporal y métricas avanzadas

---

## 🎯 Objetivos Realmente Alcanzados

En el estado actual del proyecto se han alcanzado los siguientes objetivos:

- Integración de datos de múltiples ciudades en un único modelo analítico
- Análisis descriptivo de precios y tipos de propiedad
- Comparativa visual entre mercados inmobiliarios internacionales
- Creación de un dashboard usable y orientado a negocio

El proyecto sienta una base sólida para futuras iteraciones que incluyan análisis temporal más avanzado, métricas de rendimiento y segmentaciones adicionales.

