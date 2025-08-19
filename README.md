# Proyecto de Análisis de Evasión de Clientes en TelecomX

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
<img width="585" height="402" alt="image" src="https://github.com/user-attachments/assets/c1a4bb58-f3a7-410e-b27b-284cdac53561" />
<img width="576" height="428" alt="image" src="https://github.com/user-attachments/assets/407aae29-0792-4b52-8236-8985e7bbb84b" />


2. **Evasión según variables categóricas**  
<img width="1484" height="1178" alt="image" src="https://github.com/user-attachments/assets/e1965877-6504-49c7-a7d1-aefc304402a4" />


3. **Evasión según variables numéricas**  
<img width="520" height="384" alt="image" src="https://github.com/user-attachments/assets/53cd9b07-b1f0-4fe7-8295-f60e02f0d7e8" />
<img width="560" height="384" alt="image" src="https://github.com/user-attachments/assets/9505e85f-0c84-4609-a1fe-8d3f5a377801" />
<img width="520" height="384" alt="image" src="https://github.com/user-attachments/assets/609657be-7530-411a-a7d1-d2e3d942b1ea" />


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
✍️ Autor: *[LeonelPrudencio](https://github.com/LeonelPrudencio/)*
👥 LinkedIn: *[leonel-prudencio](https://www.linkedin.com/in/leonel-antonio-prudencio-castro-9a266b292)*
📌 Proyecto de Análisis de Evasión de Clientes en TelecomX
