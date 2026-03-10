# 📦 Dashboard de Distribución Nacional - Argentina

## 📊 Descripción
Dashboard ejecutivo de análisis logístico desarrollado en Power BI 
sobre un dataset de 500K registros de distribución nacional 
Argentina 2022-2024.

## 🛠️ Tecnologías utilizadas
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M Language)

## 📈 Contenido del Dashboard

### Página 1 — Dashboard Principal
- KPIs ejecutivos: Total Entregas, % Entregas Exitosas, Costo Total
- Evolución temporal de entregas 2022-2024
- Análisis por transportista (OCA, Andreani, Correo Argentino, DHL, FedEx)
- Distribución por zona y motivo de fallo
- Segmentador interactivo por provincia

### Página 2 — Análisis Geográfico
- Mapa interactivo de Argentina por provincia
- KPI Demora Promedio
- KPI SLA Cumplido %
- Filtro geográfico por provincia

## 🧠 Modelado de datos
- Esquema estrella con tabla de hechos central
- Tabla Calendario DAX con CALENDARAUTO()
- Tabla de provincias con coordenadas geográficas
- Medidas DAX: Total Entregas, % Exitosas, SLA Cumplido

## 💡 Insights principales
- 76.78% de entregas exitosas
- Solo 10.94% cumple el SLA establecido
- Diciembre concentra los picos máximos de entregas
- OCA lidera en volumen de zona por transportista

## 📸 Vista del Dashboard

[dasbohar distribucion.pdf](https://github.com/user-attachments/files/25865064/dasbohar.distribucion.pdf)



## 👤 Autor
**Jorge Matias**  
Supply Chain Data Analyst | Power BI | Python & ML | SAP | GIS  
[LinkedIn](#) | [GitHub](https://github.com/jvillagra66-oss)
```

---

## 📁 Estructura del repositorio
```
dashboard-distribucion-nacional/
├── README.md
├── dashboard_distribucion.pbix
└── images/
    ├── pagina1.png
    └── pagina2.png
