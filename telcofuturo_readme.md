# 📊 TelcoFuturo - Análisis de Churn en Telecomunicaciones

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-FF6C37?style=for-the-badge&logo=dax&logoColor=white)

> Dashboard interactivo para identificar y reducir la tasa de abandono de clientes en el sector de telecomunicaciones colombiano.

---

## 🎯 Resumen del Proyecto

Análisis integral del comportamiento de **7,054 clientes** de TelcoFuturo para identificar patrones de abandono y generar estrategias de retención basadas en datos. El proyecto incluyó limpieza de datos, modelado y desarrollo de un dashboard ejecutivo en Power BI.

### 📈 Impacto Clave
- **27% tasa de abandono** identificada en segmentos críticos
- **53% de abandonos** causados por mal servicio (accionable)
- **$890M COP** en cargo total analizado
- **Fibra Óptica**: Servicio con mayor abandono detectado

---

## 🔍 Hallazgos Principales

| Insight | Detalle |
|---------|---------|
| **Causa #1 de Churn** | Mal servicio (53%) - oportunidad de mejora interna |
| **Causa #2** | Competencia con mejores ofertas (17%) |
| **Segmento más vulnerable** | Clientes sin socio/dependientes: 33-35% abandono |
| **Tipo de contrato crítico** | Mes a mes: mayor tasa de cancelación |
| **Servicio problemático** | Fibra Óptica: 1,298 abandonos vs 460 en DSL |
| **Método de pago** | Cheque electrónico asociado a mayor churn |

---

## 🛠️ Tecnologías y Habilidades

**Herramientas:**
- Power BI Desktop (Visualización y DAX)
- Microsoft Excel (Limpieza y preparación de datos)
- Power Query (Transformaciones ETL)

**Técnicas Aplicadas:**
- Análisis de Churn y Retención de Clientes
- Segmentación de Clientes (por género, contrato, servicios)
- Modelado de Datos (Relaciones y medidas DAX)
- Storytelling con Datos
- Business Intelligence

---

## 📊 Estructura del Dashboard

El dashboard interactivo incluye:

1. **KPIs Principales**
   - Cargo Total y Mensual
   - Tasa de Abandono por Género
   - Contador de Clientes Activos/Inactivos

2. **Análisis de Causas**
   - Gráfico de dona con distribución de motivos de abandono
   - Drill-down por segmento de cliente

3. **Análisis de Servicios**
   - Internet (Fibra Óptica vs DSL vs Sin servicio)
   - Streaming (Películas y TV por tipo de contrato)
   - Métodos de pago y su relación con churn

4. **Filtros Interactivos**
   - Género (Masculino/Femenino)
   - Socio (Sí/No)
   - Persona Mayor (0/1)
   - Dependientes (Sí/No)

---

## 📁 Estructura del Proyecto

```
telcofuturo-churn-analysis/
│
├── data/
│   ├── raw/                    # Datos originales
│   └── cleaned/                # Datos limpios (Excel)
│
├── powerbi/
│   └── TelcoFuturo_Dashboard.pbix
│
├── docs/
│   ├── INFORME_COMPLETO.pdf
│   └── METODOLOGIA.md
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🚀 Recomendaciones Estratégicas

Basado en el análisis de datos, se proponen **5 acciones prioritarias**:

### 1️⃣ **Mejora de Calidad de Servicio** (Crítico)
- Capacitación en atención al cliente y habilidades blandas
- Sistema de seguimiento de satisfacción en tiempo real
- **Meta**: Reducir abandono por mal servicio de 53% a <30% en 6 meses

### 2️⃣ **Retención de Clientes Vulnerables**
- Ofertas personalizadas para clientes sin socio/dependientes
- Programa de beneficios para contratos anuales
- **Meta**: Disminuir churn del segmento de 33% a 20%

### 3️⃣ **Optimización de Infraestructura**
- Auditoría técnica de Fibra Óptica
- Plan de mejora de conectividad DSL
- **Meta**: Reducir abandonos por servicio técnico en 40%

### 4️⃣ **Estrategia Competitiva**
- Benchmarking de ofertas del mercado
- Paquetes personalizados por tipo de cliente
- **Meta**: Recuperar 10% de clientes perdidos por competencia

### 5️⃣ **Migración a Contratos Anuales**
- Incentivos para cambio de mes a mes a anual
- Descuentos progresivos por fidelización
- **Meta**: Aumentar contratos anuales en 25%

---

## 📌 Metodología

### Limpieza de Datos (Excel)
- Eliminación de duplicados y errores de digitación
- Corrección de inconsistencias sistemáticas
- Estandarización de formatos
- **Registros eliminados**: 2 (IDs con errores: 5129-JLPIS, 4929-XIHVW)

### Modelado en Power BI
- Importación de datos limpios
- Creación de medidas DAX personalizadas
- Diseño de relaciones entre tablas
- Desarrollo de visualizaciones interactivas

### Análisis Segmentado
- 8 perfiles de cliente analizados
- Variables: Género, Socio, Dependientes, Persona Mayor
- Comparación cruzada de comportamientos

---

## 👤 Autor

**Aarón Mateo Tocora Jiménez**
- 📍 Bogotá D.C., Colombia
- 🎓 Proyecto: Data Riders - Corte 13°
- 📅 Abril 2024

---

## 📄 Licencia

Este proyecto es de uso educativo y demostrativo para portafolio profesional.

---

## 🔗 Enlaces Útiles

- [Documentación de Power BI](https://docs.microsoft.com/power-bi/)
- [Guía de DAX](https://dax.guide/)
- [Best Practices en BI](https://powerbi.microsoft.com/blog/)

---

**⭐ Si este proyecto te resultó útil, considera darle una estrella en GitHub**