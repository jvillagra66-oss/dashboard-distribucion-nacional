# 📦 Dashboard de Distribución Nacional - Argentina

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-M%20Language-informational)
![SAP](https://img.shields.io/badge/ERP-SAP%20TM-blue)
![Status](https://img.shields.io/badge/Status-Producción-brightgreen)

---

## 🎯 Problema de Negocio

En Argentina, las empresas de distribución logística enfrentan 
**altos índices de incumplimiento de SLA** y demoras operativas 
que impactan directamente en:

- 📦 Costos de reenvío y gestión de devoluciones
- 😟 Satisfacción del cliente final
- 📉 Margen operativo del transportista
- 🏭 Sobrecarga en centros de distribución

Este dashboard permite identificar **dónde, cuándo y por qué 
fallan las entregas** para tomar decisiones basadas en datos.

---

## 📊 Descripción

Dashboard ejecutivo de análisis logístico desarrollado en 
**Power BI** sobre un dataset de **500K registros** de 
distribución nacional Argentina 2022-2024.

---

## 🛠️ Tecnologías utilizadas

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M Language)
- Modelado estrella (Star Schema)

---

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

---

## 🧠 Modelado de datos

- Esquema estrella con tabla de hechos central
- Tabla Calendario DAX con CALENDARAUTO()
- Tabla de provincias con coordenadas geográficas
- Medidas DAX: Total Entregas, % Exitosas, SLA Cumplido

---

## 💡 Insights principales

- **76.78%** de entregas exitosas
- Solo **10.94%** cumple el SLA establecido
- Diciembre concentra los picos máximos de entregas
- OCA lidera en volumen de zona por transportista

---

## 📸 Vista del Dashboard

📄 [dasbohar distribucion.pdf](https://github.com/user-attachments/files/25866158/dasbohar.distribucion.pdf)


---

## 🔗 Proyecto relacionado

🤖 **[Sistema ML de Predicción de Fallos — Última Milla](https://github.com/jvillagra66-oss/sistema-prediccion-fallos-ultima-milla)**  
Sistema de Machine Learning que predice fallos logísticos 
usando los mismos datos de distribución nacional.

---

## 👤 Autor

**Jorge Matias**  
Supply Chain Data Analyst | Power BI | Python & ML | SAP | GIS  
🇦🇷 Argentina | Open to remote opportunities  
[LinkedIn](#) | [GitHub](https://github.com/jvillagra66-oss)
