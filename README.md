# Análisis de E-Commerce Olist — ML No Supervisado
**Universidad de La Sabana · 2026-I · Prof. E. Carrillo B. Ana Luzia Ferrer Mendez**

---

## Descripción

Proyecto de análisis de datos aplicado al dataset Brazilian E-Commerce by Olist,
desarrollado en el rol de analista de datos bajo el marco metodológico CRISP-DM.
El análisis responde la pregunta central:

> *¿Qué tan predecible y sostenible es la operación logística de Olist, y qué
> segmentos geográficos y de cliente concentran el mayor riesgo de insatisfacción
> y costo?*

---

## Dataset

**Fuente:** [Brazilian E-Commerce by Olist — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
**Licencia:** CC BY-NC-SA 4.0  
**Período:** Septiembre 2016 — Octubre 2018  
**Registros:** +100,000 órdenes

### Archivos utilizados

| Archivo | Rol en el análisis |
|---|---|
| `olist_orders_dataset.csv` | Eje central. Tiempos de entrega y retraso. |
| `olist_order_items_dataset.csv` | Costos de flete por orden. |
| `olist_order_reviews_dataset.csv` | Satisfacción del cliente (review_score). |
| `olist_customers_dataset.csv` | Ubicación geográfica del comprador. |
| `olist_geolocation_dataset.csv` | Coordenadas lat/lng por CEP. |
| `olist_products_dataset.csv` | Categoría y dimensiones físicas del producto. |
| `product_category_name_translation.csv` | Traducción de categorías al inglés. |

---

## Metodología

El análisis sigue el marco **CRISP-DM** en seis fases:

1. **Business Understanding** — Definición de la pregunta central y preguntas por técnica.
2. **Data Understanding** — Exploración de 7 archivos CSV, análisis de nulos, cobertura relacional y cardinalidad.
3. **Data Preparation** — Construcción de variables derivadas y tabla maestra de 95,533 filas.
4. **Modeling** — Aplicación de cuatro técnicas de ML no supervisado.
5. **Evaluation** — Validación técnica y de negocio de cada modelo.
6. **Deployment** — Tres recomendaciones ejecutivas accionables.

---
