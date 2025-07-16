# 📊 Dashboard Checklist 5s - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a Power Apps, orientado al análisis de los resultados de las auditorías de 5's

---

## 📌 Objetivo

Diseñar un tablero en Power BI para medir y visualizar los resultados de las auditorías 5’s en la planta, permitiendo dar seguimiento al cumplimiento de los estándares, identificar áreas de oportunidad y fomentar la mejora continua en orden, limpieza y disciplina operativa.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- Power Apps (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
Checklist-5S/
├── pbix/                                   → Archivo PBIX del tablero
│── README.md                               → Descripción general del repositorio
├── docs/
│   ├── ColumnasCalculadas.md               → DAX documentadas
│   ├── Tablas_DAX.md                       → DAX documentadas
│   └── video_tutorial.md                   → Guía de uso del dashboard
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   └── modelo_datos.png                    → Relación entre tablas
└── LICENSE                                 → MIT (u otra que se defina)
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/Dashboard_OEE_Coflex.pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

---

## 📄 Licencia

MIT – Libre uso con atribución.
