# Análisis de Embudo de Conversión y Retención (E-commerce)

## 🎯 Objetivo del Proyecto
Analizar el comportamiento de los usuarios en una plataforma de e-commerce para identificar en qué etapas del proceso de compra se pierde la mayor cantidad de clientes y medir la lealtad a través de cohortes de retención.

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** SQL (PostgreSQL)
* **Técnicas:** * Common Table Expressions (CTEs) para organizar la lógica.
    * Funciones de agregación y filtros temporales.
    * Cálculo de tasas de conversión y retención por cohortes.

## 📊 Análisis Realizado
1. **Embudo de Ventas (Funnel):** Seguimiento desde la visita inicial (`first_visit`) hasta la compra final (`purchase`).
2. **Segmentación Geográfica:** Comparativa de comportamiento por países.
3. **Retención de Usuarios:** Análisis de recurrencia a los 7, 14, 21 y 28 días después del registro.

## 💡 Conclusiones Clave
* Se identificaron las etapas con mayor tasa de abandono en el checkout.
* La retención varía significativamente por país, lo que sugiere adaptar estrategias de marketing locales.

---
*Proyecto desarrollado como parte del Bootcamp de Data Analyst en TripleTen (2025).*
