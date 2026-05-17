# Hola — soy Gerardo 👋

Analista de datos en México. Me interesa una cosa: que los datos terminen en una decisión, no en un slide deck que nadie vuelve a abrir.

He construido proyectos end-to-end donde el entregable no es solo un dashboard o un notebook — es un hallazgo que cambia la lectura del negocio. Como descubrir que el +11% de crecimiento de una empresa inmobiliaria es insostenible porque la adquisición de clientes cayó 67%, o que una landing page B genera $7.66 más por usuario convertido con un p-value de 1.06e-20.

---

## 🛠️ Stack & herramientas

**Lenguajes & análisis**
`Python` · `SQL` · `PostgreSQL`

**Librerías**
`Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SciPy` · `Statsmodels`

**Estadística aplicada**
`Prueba t de Student` · `Prueba Z de proporciones` · `Chi-cuadrada` · `A/B Testing` · `Prueba de Levene`

**Visualización & BI**
`Power BI` · `DAX` · `Google Sheets`

**Modelado de datos**
`Esquema estrella` · `Tablas de hechos y dimensiones` · `Análisis de cohortes`

**Entorno de trabajo**
`Google Colab` · `Jupyter Notebook` · `DBeaver`

---

## 📂 Proyectos destacados

### 🏗️ [Grupo Andes — Análisis Comercial Inmobiliario](https://github.com/gerardovazquez-DataAnalyst/grupo-andes-analisis-inmobiliario)
> Dashboard de 3 vistas en Power BI con narrativa SCQA — el hallazgo principal: el +11% YoY es insostenible.

- Construí un modelo estrella con 23 medidas DAX organizadas en 8 carpetas funcionales y 4 columnas calculadas para análisis de cohortes
- Diseñé deltas dinámicos bidireccionales con `SELECTEDVALUE` + `REMOVEFILTERS` que comparan cualquier año contra el otro y desaparecen cuando ambos están seleccionados
- Descubrí que Departamento vende 60% del volumen pero solo genera 31% del ingreso — un scatter plot de paradoja volumen vs ingreso que cambió la recomendación comercial
- Revelé que la adquisición de clientes cayó 67% (197→64/mes) y el ingreso de primera compra pasó de 61% a 18%, exponiendo que el crecimiento se sostiene por inercia de recompra, no por nueva demanda
- **Stack:** Power BI · DAX · Python · Pandas

---

### 🟣 [Landing Page A/B Test — Conversion & Revenue Analysis](https://github.com/gerardovazquez-DataAnalyst/ab-testing-landing-page)
> Análisis estadístico de un experimento A/B — 40,000 usuarios, 28 días, 4 pruebas estadísticas, una decisión.

- Apliqué prueba t de Student + Levene para comparar gasto promedio: página B genera $7.66 más por usuario convertido ($68.75 vs $61.09), con p-value de 1.06e-20
- Confirmé vía prueba Z de proporciones que página B convierte 3.38pp más (15.96% vs 12.57%), con p-value de 3.76e-22
- Descubrí que el tipo de usuario (Nuevo vs Recurrente) no tiene impacto estadísticamente significativo en la conversión (p=0.474) — eliminando una variable de segmentación sin respaldo en datos
- **Stack:** Python · Pandas · SciPy · Statsmodels · Matplotlib · Seaborn

---

### 🟠 [Olist — Brazilian E-Commerce Analysis](https://github.com/gerardovazquez-DataAnalyst/olist-ecommerce-analysis)
> Análisis SQL end-to-end de ~100K órdenes de un marketplace brasileño — Revenue, Operaciones y Experiencia del Cliente.

- Identifiqué que Health & Beauty lideró el revenue por volumen, no por precio — con implicaciones directas para estrategias de upselling
- Descubrí que el Nordeste concentraba los peores tiempos de entrega del país y correlacionaba con una caída de ~1.5 estrellas en satisfacción
- Construí una capa de vistas en PostgreSQL como interfaz limpia hacia Power BI
- **Stack:** SQL · PostgreSQL · DBeaver · Power BI

---

### 🔵 [ConnectaTel — Customer Behavior Analysis & Churn Segmentation](https://github.com/gerardovazquez-DataAnalyst/connectatel_customer_analysis)
> Análisis de comportamiento de clientes y segmentación de churn para una empresa de telecomunicaciones LATAM.

- Identificación de desalineación oferta-comportamiento: usuarios de alto uso pagando excedentes superiores al costo del plan Premium
- Detección de churn silencioso en usuarios de bajo uso sin señales previas visibles
- **Stack:** Python · Pandas · Seaborn · Matplotlib · SciPy

---

## 📫 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gerardo%20Vázquez-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/gerardo-vazquez-dataanalyst)

---

*Monterrey, México · Abierto a oportunidades en Data Analytics*
