# Proyecto: Análisis de Evasión de Clientes en Telecomunicaciones

## 📌 Descripción
Este proyecto analiza los patrones de **evasión de clientes (Churn)** en el sector de telecomunicaciones, utilizando el dataset **TelecomX**.  
El objetivo fue **identificar factores clave que explican el abandono** y proponer estrategias de retención basadas en insights de negocio.

## 📂 Dataset
Se utilizó la base de datos disponible en:  
[TelecomX_Data.json](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json)

**Principales variables**: tipo de contrato, antigüedad, servicios contratados, método de pago, soporte técnico y cargos.

## ⚙️ Proceso
1. **Limpieza y Transformación**
   - Eliminación de duplicados y nulos.
   - Expansión de variables y estandarización de nombres.
   - Conversión de tipos de datos (categóricos, numéricos y booleanos).

2. **Análisis Exploratorio (EDA)**
   - Distribución de la evasión.
   - Relación con variables categóricas y numéricas.
   - Identificación de patrones de abandono según contrato, servicio de internet, método de pago y soporte técnico.

## 📊 Principales Gráficas

1. **Distribución general de evasión**  


2. **Evasión según tipo de contrato**  


3. **Evasión según tipo de servicio de internet**  


4. **Evasión según método de pago**  


5. **Distribución por antigüedad del cliente**  


6. **Relación cargos mensuales y evasión**  


## 🔍 Insights Clave
- **Contrato**: 88.7% de abandonos son contratos mes a mes; los contratos anuales y bienales muestran mayor lealtad.  
- **Servicio de Internet**: Fibra óptica concentra 92.6% de los abandonos.  
- **Método de Pago**: Electronic check explica más del 50% de los abandonos; pagos automáticos reducen el churn.  
- **Soporte Técnico**: 81% de los que abandonan no contaban con soporte técnico.  
- **Antigüedad**: La mayoría de abandonos ocurre en los primeros 6–12 meses.  
- **Cargos**: Clientes con planes intermedios y mayor gasto acumulado muestran menor tasa de abandono.

## 🎯 Recomendaciones Estratégicas
- **Scoring de riesgo** para clientes nuevos con baja facturación y pagos manuales.  
- **Programa de acompañamiento en los primeros 6 meses** con ofertas y contacto proactivo.  
- **Incentivos por cambio a pagos automáticos**.  
- **Protocolos de retención para clientes con reclamos recurrentes**.  
- **Acciones específicas en umbrales de antigüedad y facturación acumulada**.

---
✍️ Autor: *Leo Castro*  
📌 Proyecto de Análisis de Evasión de Clientes en Telecomunicaciones
