# 📊 Proyecto TelecomX – Análisis de Evasión de Clientes (Churn)

## 🚀 Descripción
Este proyecto realiza un análisis exhaustivo de los datos de clientes de **TelecomX** con el objetivo de identificar los factores críticos que influyen en la fuga/evasión de clientes (churn). El análisis reveló una **tasa de churn del 26.54%**, considerablemente superior al benchmark saludable de la industria (15-20%), representando una pérdida significativa de ingresos estimada en **$1.67 millones anuales**.

## 🎯 Objetivo
- **Identificar patrones** de comportamiento en clientes que abandonan el servicio
- **Analizar factores críticos** que impulsan la evasión
- **Desarrollar insights estratégicos** basados en análisis descriptivo y estadístico
- **Generar recomendaciones** accionables para reducir el churn
- **Establecer base** para futuros modelos predictivos de Machine Learning

## 🛠️ Tecnologías Utilizadas
- **Python 3.10+**
- **Pandas, NumPy** - Manipulación y análisis de datos
- **Matplotlib, Seaborn** - Visualización de datos
- **Jupyter Notebook / Google Colab** - Entorno de desarrollo

## 📊 Análisis Realizado

### **🔍 Análisis Exploratorio Completo**
- **Limpieza y normalización** de 7,043 registros válidos
- **Transformación** de variables categóricas y numéricas
- **Análisis estadístico** con pruebas de significancia
- **Identificación** de 13 variables significativas de 15 analizadas

### **📈 Análisis por Dimensiones**
1. **Variables Categóricas:**
   - Tipo de contrato (39.9% diferencia en churn)
   - Servicio de internet (34.5% diferencia)
   - Método de pago (30.0% diferencia)
   - Perfil demográfico y servicios adicionales

2. **Variables Numéricas:**
   - Antigüedad de clientes (correlación -0.3522)
   - Cargos mensuales y totales
   - Análisis de distribuciones comparativas

3. **Visualizaciones Estratégicas:**
   - Gráficos de barras para tasas de churn
   - Histogramas comparativos por segmento
   - Box plots para análisis de distribuciones
   - Análisis de correlaciones numéricas

## 🔍 Principales Hallazgos

### **🚨 Descubrimientos Críticos**
1. **Paradoja del Cliente Premium:** Los clientes de fibra óptica (41.9% churn) y con mayores cargos mensuales ($74.4 vs $61.3) son los más propensos a irse
2. **Ventana Crítica:** Los primeros 18 meses son decisivos (clientes que se van: 18.0 meses vs 37.6 meses de antigüedad)
3. **Efecto Compromiso:** Contratos mes a mes tienen 42.7% churn vs contratos largos
4. **Riesgo Demográfico:** Ciudadanos mayores (41.7% churn) y personas sin dependientes (31.3% churn)

### **👤 Perfil de Alto Riesgo Identificado**
- Contrato mes a mes
- Servicio de fibra óptica  
- Pago con cheque electrónico
- Ciudadano mayor sin dependientes
- Menos de 18 meses de antigüedad
- Cargo mensual > $70

## 🚀 Recomendaciones Estratégicas

### **⚡ Acciones Inmediatas (ROI 250%+)**
1. **Programa de Onboarding Intensivo** - Target: clientes <6 meses
2. **Revisión de Estrategia Premium** - Mejorar propuesta de valor fibra óptica
3. **Migración a Contratos Largos** - Incentivos para compromisos anuales/bianuales

### **📈 Impacto Proyectado**
- **Reducción de churn objetivo:** De 26.54% a 20%
- **Retención adicional:** 460+ clientes/mes
- **Incremento de ingresos:** $400K+ anuales recurrentes

## 🔧 Cómo Ejecutar el Proyecto

### **📋 Requisitos Previos**
```bash
Python >= 3.10
pandas >= 1.5.0
numpy >= 1.24.0
matplotlib >= 3.6.0
seaborn >= 0.12.0
jupyter >= 1.0.0
```

### **🚀 Instalación y Ejecución**

1. Abre [Google Colab](https://colab.research.google.com/)
2. Sube el archivo `TelecomX_Analisis_Churn.ipynb`
3. Ejecuta la primera celda para instalar dependencias
4. Ejecuta todas las celdas secuencialmente

### **📊 Fuente de Datos**
Los datos se cargan automáticamente desde:
```python
url = "https://raw.githubusercontent.com/7PartidasDigital/Challenge-Data-Science/main/TelecomX_Data.json"
```

## 📈 Estructura del Análisis en el Notebook

### **🗂️ Secciones Principales**
1. **📥 Importación y Configuración** - Librerías y configuración inicial
2. **🔄 Extracción y Limpieza** - Carga desde JSON y normalización
3. **🧹 Preparación de Datos** - Transformaciones y estandarización
4. **📊 Análisis Exploratorio** - EDA categórico y numérico completo
5. **📈 Visualizaciones** - Gráficos estratégicos por variable
6. **💡 Insights y Conclusiones** - Hallazgos críticos identificados
7. **📋 Informe Final** - Evaluación de Insights y recomendaciones

## 🎯 Métricas de Éxito del Proyecto

### **📊 KPIs Identificados (Métricas Clave)**
- **Tasa de Churn General:** 26.54% → Target 20%
- **Churn Contratos M2M:** 42.7% → Target 25%
- **Churn Fibra Óptica:** 41.9% → Target 30%
- **Retención Clientes Nuevos:** 60% → Target 75%

### **💰 Impacto Económico Proyectado**
- **Pérdida Actual:** $1.67M anuales
- **Ahorro Potencial:** $400K+ anuales
- **ROI Estrategias:** 250-400% primer año

## 📄 Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles.

## 👤 Autor
**Proyecto desarrollado por:** Londero Guillermo Humberto  
**Programa:** ONE + Alura LATAM - Especialización en Ciencia de Datos  
**Fecha:** Agosto 2025  

### **📞 Contacto**
- **LinkedIn:** www.linkedin.com/in/guillermo-londero
- **GitHub:** https://github.com/GuilleLondero
- **Email:** guillelondero@gmail.com

## 🏆 Reconocimientos
- **Alura + ONE LATAM** por la estructura del desafío
- **Comunidad Data Science** por recursos y mejores prácticas

---

⭐ **Si este proyecto te fue útil, no olvides darle una estrella en GitHub!**

📊 **#DataScience #ChurnAnalysis #TelecomAnalytics #PythonAnalysis #AluraONE**
