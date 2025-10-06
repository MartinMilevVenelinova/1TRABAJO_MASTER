# 🛡️ Análisis de Ciberseguridad: Dashboard Interactivo en Excel

## 📖 Descripción del Proyecto
Este proyecto realiza un **análisis exploratorio y descriptivo** de una base de datos de **incidentes de ciberseguridad** entre los años 2015 y 2024.  
El objetivo es **identificar patrones, pérdidas económicas, sectores más afectados y la efectividad de los mecanismos de defensa** utilizados ante los ataques.

El trabajo se desarrolló íntegramente en **Microsoft Excel**, aplicando:
- Limpieza y estandarización de datos.  
- Creación de **tablas dinámicas** para resumir información.  
- Diseño de un **dashboard interactivo** con KPIs, gráficos y segmentadores.  

Este análisis ayuda a visualizar de forma clara **dónde, cómo y con qué rapidez** se resuelven los ciberataques, y qué sectores sufren mayores pérdidas.

---

## 🗂️ Estructura del Proyecto

```
ProyectoCiberseguridad/
├── ProyectoExcel.xlsx        # Archivo principal con datos, KPIs y Dashboard
│   ├── Hoja “Global_Cybersecurity_Threats” → Base de datos limpia
│   ├── Hoja “KPIS” → Indicadores clave y cálculos agregados
│   ├── Hoja “Tablas_dinamicas” → Análisis y pivots de soporte
│   └── Hoja “Dashboard” → Visualización final e interactiva
├── README.md                 # Este documento
├── docs/                     # Word con documentacion adicional
└── Global_Cybersecurity_Threats_dirty.csv    # Archivo original de la Base de datos
```

---

## 🛠️ Instalación y Requisitos

Este proyecto no requiere instalación de bibliotecas externas.  
Solo necesitas:

- 💻 **Microsoft Excel 2019 / Office 365 o superior**  
- Habilitar macros opcionalmente si se desea automatizar actualizaciones (no obligatorio)  

**Para ejecutar el análisis:**
1. Abre el archivo `ProyectoExcel.xlsx`.  
2. Dirígete a la hoja **Dashboard**.  
3. Usa los **segmentadores** (Año, Región, Tipo de ataque, Industria) para explorar los resultados.  

---

## 📊 Resultados y Conclusiones

### 🔹 Indicadores principales (KPIs)
- 💰 **Pérdida económica total:** muestra el impacto monetario de los ataques.  
- ⏱ **Tiempo medio de resolución (h):** promedio de horas necesarias para solucionar incidentes.  
- 🧩 **Incidentes totales:** cantidad de registros de ataques.  
- 🏭 **Industria más afectada:** sector con mayor pérdida acumulada.  

Estos indicadores se actualizan automáticamente al aplicar filtros en el dashboard.

### 🔹 Principales hallazgos
- Las regiones de **Europa y Asia** concentran la mayor pérdida económica total.  
- Los ataques más frecuentes y dañinos son **Phishing** y **DDoS**.  
- **Encryption** y **Firewall** son los mecanismos de defensa con **mayor efectividad**, logrando más resoluciones rápidas.  
- Los sectores **Telecomunicaciones** y **Retail** presentan las pérdidas más altas.  
- La tendencia general muestra un **aumento constante de ataques** hasta 2023.

### 🔹 Visualizaciones incluidas
- Distribución de pérdidas por **Región** e **Industria** (gráficos de anillo en %).  
- Evolución de **Incidentes por Año** (línea temporal).  
- **Usuarios afectados por Tipo de Ataque** (barras horizontales).  
- **Top 5 países con mayores pérdidas económicas** (barras ordenadas).  
- **Relación entre pérdidas y usuarios** (gráfico combinado).  
- **Efectividad de defensa** (barras agrupadas por % Rápida, Media, Tardía).

---

## 🔄 Próximos Pasos

- Añadir un **mapa geográfico interactivo** para mostrar pérdidas por país. (Se dificulto)  
- Incluir **medidas estadísticas** adicionales (p. ej., mediana o desviación en tiempos de resolución).  
- Publicar la versión avanzada del dashboard en **Power BI**.  
- Incorporar un análisis de **tendencias de defensa** a lo largo de los años.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas.  
Si deseas mejorar el dashboard o añadir nuevas visualizaciones:
1. Abre una *issue* o comentario con la propuesta.  
2. Explica brevemente el cambio sugerido.  
3. Si aplicable, comparte una versión actualizada del archivo Excel.  

---

## ✒️ Autores y Agradecimientos

**Autor:** Martin Milev Venelinova
**Formación:** Big Data Analytics  
