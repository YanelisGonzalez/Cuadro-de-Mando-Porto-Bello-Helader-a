# Cuadro-de-Mando-Porto-Bello-Heladería

# 📊 Dashboard de Ventas – Heladería Artesanal Italiana Porto Bello (Power BI)

## 📌 Descripción del Proyecto
Proyecto de análisis y visualización de datos desarrollado en **Power BI** para una heladería artesanal ubicada en Madrid.  
El objetivo del proyecto es transformar los datos de ventas en información visual y accionable que facilite la **toma de decisiones estratégicas y operativas**.

El dashboard permite analizar el rendimiento de las ventas, identificar patrones de consumo, estacionalidad y productos clave, sustituyendo decisiones basadas en intuición por decisiones basadas en datos.

---

## 🎯 Objetivos del Análisis
- Obtener una visión global de las ventas.
- Analizar el comportamiento de las ventas por producto, categoría y período.
- Detectar patrones de estacionalidad, días y horas pico.
- Identificar productos de alta y baja rotación.
- Apoyar la optimización de inventarios y estrategias comerciales.

---

## 📊 Fuentes de Datos
Los datos utilizados provienen de registros internos del negocio (datos simulados para fines académicos):

### 1️⃣ Registro de Ventas (POS)
- Fecha y hora de la venta  
- Código y nombre del producto  
- Cantidad vendida  
- Precio unitario y total  

### 2️⃣ Catálogo de Productos
- Categorías (helados, batidos, granizados, postres)  
- Coste unitario  
- Precio de venta  

Las fuentes se integraron en Power BI para construir un **modelo relacional** que permite el análisis temporal y por producto.

---

## 🛠️ Herramientas Utilizadas
- **Power BI**
- **Power Query** (limpieza y transformación de datos)
- **DAX** (medidas y métricas)
- **Excel / CSV**

---

## 🧹 Preparación y Transformación de Datos
### Limpieza de datos (Power Query)
- Eliminación de duplicados  
- Corrección de errores tipográficos  
- Tratamiento de valores nulos  
- Normalización de formatos (fechas, texto, números)

### Transformaciones
- Creación de columnas calculadas  
- Cálculo de totales, promedios y porcentajes  
- Integración y cruce de múltiples fuentes  
- Filtrado de registros irrelevantes  

---

## 🧩 Modelado de Datos
- Modelo en **estrella**
- **Tabla de hechos:** Ventas  
- **Tablas de dimensiones:** Producto, Categoría, Tiempo  
- Dimensión de fechas generada mediante **DAX**
- Relaciones 1:* para asegurar eficiencia analítica

---

## 📈 KPIs Principales
### KPIs de Ventas
- Ventas Totales (€)
- Número de Transacciones
- Ticket Promedio (€)
- Crecimiento de Ventas (%)
- Ventas por Categoría
- Producto más vendido

### KPIs Operativos
- Ventas por hora, día, mes y año
- Día y hora pico de ventas
- Producto más vendido en hora pico

---

## 📊 Diseño del Dashboard
El dashboard está organizado en varias páginas:

- **Resumen General:**  
  KPIs principales y visión global de ventas por período y categoría.

- **Análisis Temporal:**  
  Ventas por hora, día, mes y tipo de día (laboral / fin de semana).

- **Análisis por Producto:**  
  Cantidades vendidas, ranking de productos y productos sin rotación.

- **Análisis de Ventas por Producto:**  
  Evolución temporal y ventas acumuladas.

- **Análisis por Año:**  
  Comparativa anual por producto y categoría.

Incluye segmentadores por **año, trimestre, mes, producto y categoría**, permitiendo análisis interactivo y cruzado.

---

## 💡 Insights Clave
- Mayor volumen de ventas en fines de semana.
- Horas pico concentradas en el horario de merienda.
- Alta estacionalidad: mayor demanda en primavera/verano.
- Existencia de productos con baja o nula rotación.
- Oportunidades de optimización de stock y recursos.

---

## 🚀 Recomendaciones Estratégicas
- Priorizar productos de mayor demanda.
- Ajustar inventarios según estacionalidad.
- Eliminar o replantear productos sin rotación.
- Lanzar promociones en días y períodos de baja venta.
- Reforzar personal y stock en horas y días pico.
- Aplicar estrategias de fidelización y marketing local.

---

## 🧠 Conclusiones
Este proyecto demuestra cómo un dashboard en Power BI puede:
- Convertir datos crudos en información clara y visual.
- Detectar patrones de consumo y oportunidades de mejora.
- Apoyar decisiones estratégicas basadas en datos.
- Mejorar la eficiencia operativa y la rentabilidad del negocio.

---

## 👩‍💻 Autora
**Yanelis González**  
Ingeniera Industrial | Data Analyst  

🔗 GitHub: https://github.com/YanelisGonzalez/YanelisGonzalez.git  
🔗 LinkedIn: https://www.linkedin.com/in/yanelis-gonzález-gonzález-973979104/
