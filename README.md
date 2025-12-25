# 📊 TelecomX LATAM — Análisis de Evasión de Clientes (Churn)

## 🔎 Descripción general

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** enfocado en comprender la **evasión de clientes (Churn)** en una empresa de telecomunicaciones ficticia (*TelecomX LATAM*).

El objetivo principal es **identificar los factores más influyentes en la cancelación del servicio**, detectar patrones de riesgo y proponer **recomendaciones estratégicas basadas en datos** para apoyar la toma de decisiones orientadas a la retención de clientes.

---

## 🎯 Objetivos del proyecto

- Analizar la **distribución del churn** en la base de clientes.
- Explorar la relación entre churn y variables **categóricas** y **numéricas**.
- Identificar variables con **mayor influencia** sobre la evasión.
- Generar **insights accionables** para reducir el churn.
- Dejar una base preparada para un futuro **modelo predictivo**.

---

## 🧠 Principales hallazgos (Insights)

- **Tipo de contrato (`account.Contract`)**  
  La evasión es considerablemente mayor en contratos **mensuales**; contratos de mayor duración presentan menor churn.

- **Antigüedad del cliente (`customer.tenure`)**  
  El churn se concentra en los **primeros meses**. A mayor antigüedad, menor probabilidad de evasión.

- **Método de pago (`account.PaymentMethod`)**  
  El método **Electronic check** muestra mayor churn, mientras que los métodos de pago **automáticos** presentan mayor retención.

- **Servicios de valor agregado**  
  - **Soporte técnico (`internet.TechSupport`)**: asociado a menor churn cuando está activo.  
  - **Seguridad online (`internet.OnlineSecurity`)**: asociado a menor churn cuando está activa.

- **Costo diario (`Cuentas_Diarias`)**  
  Los clientes que evaden tienden a presentar **costos diarios más altos**, aunque este factor actúa de forma complementaria.

---

## 🏆 Ranking de variables más influyentes (EDA)

1. Tipo de contrato  
2. Antigüedad del cliente (tenure)  
3. Soporte técnico / Seguridad online  
4. Método de pago  
5. Costo diario del servicio (`Cuentas_Diarias`)  
6. Variables demográficas (impacto menor)

> Este ranking se basa en patrones observados durante el análisis exploratorio y **no implica causalidad directa**.

---

## 🛠️ Tecnologías utilizadas

* Python 3

* Pandas

* NumPy

* Matplotlib/ Seaborn

* Jupyter Notebook / Google Colab

---
---
## ▶️ Cómo ejecutar el proyecto
* Google Colab (recomendado)

    * Abrir el archivo TelecomX_LATAM.ipynb en Google Colab.

    * Ejecutar las celdas en orden, de arriba hacia abajo.

    * Revisar gráficos, análisis e informe final dentro del notebook.

---
---

## 🧪 Flujo de trabajo

1. Carga y exploración inicial de los datos.

2. Normalización de estructuras anidadas.

3. Limpieza y estandarización de variables.

4. Transformación de variables binarias (Yes/No → 0/1).

5. Creación de la variable Cuentas_Diarias.

6. Análisis Exploratorio de Datos (EDA) con visualizaciones.

7. Interpretación de resultados.

8. Conclusiones y recomendaciones estratégicas.

---

## 📌 Recomendaciones estratégicas

* Incentivar contratos de mayor duración.

* Implementar retención temprana en clientes nuevos.

* Promover el uso de pagos automáticos.

* Ofrecer bundles de servicios con soporte técnico y seguridad online.

* Priorizar clientes con alto riesgo de churn para acciones preventivas.

---

## 👤 Autor

- **Daniel Gallardo**
- 📍 Chile
- 📊 Científico de Datos en formación
- 💡 Interés en análisis de datos, automatización y toma de decisiones basadas en datos

---
