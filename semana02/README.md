# 🛒 Semana 02: Consultas SQLite para Responder Preguntas de Negocio

![Tema](https://img.shields.io/badge/Tema-SQL%20%7C%20Filtrado%20y%20Agregaci%C3%B3n-blue)
![Entorno](https://img.shields.io/badge/Entorno-Google%20Colab-orange)
![Base%20de%20Datos](https://img.shields.io/badge/BD-TecnoAndina%20Retail-green)

---

## 📌 Objetivos de la Semana

- Ejecutar consultas **SQL (SQLite)** para filtrar, ordenar y limitar registros utilizando cláusulas como `WHERE`, `ORDER BY` y `LIMIT`.
- Aplicar **funciones de agregación** (`COUNT`, `SUM`, `AVG`, `MAX`, `MIN`) para obtener métricas clave de ventas.
- Interpretar los resultados de las consultas desde una perspectiva de negocio y gestión de datos.
- Argumentar decisiones comerciales analizando el balance entre volumen de ventas e ingresos recaudados.

---

## 🗃️ Caso de Estudio: TecnoAndina Retail

El análisis opera sobre la tabla `ventas` que registra las transacciones de **TecnoAndina Retail** en cuatro sedes principales (*Lima, Piura, Trujillo y Arequipa*) durante un período de evaluación de 6 días (72 transacciones).

### Archivos de la Sesión:
- 📓 **Cuaderno Principal:** `FDG_EDIR_GONZANO_ROJAS.ipynb`

---

## 🚀 Contenido Desarrollado

1. **Filtros Avanzados y Muestreo:** Análisis de compras en canal Web y filtrado por categoría/sede.
2. **Métricas Agregadas:** Comparativa de rendimiento comercial entre las sedes de Lima y Piura.
3. **Retos de Aplicación:**
   - **Reto 1:** Evaluación de tickets más altos en Cómputo para la sede Trujillo.
   - **Reto 2:** Análisis de volumen de ventas vs. margen de ganancia en Accesorios.
   - **Reto 3:** Desmitificación de volumen vs. valor acumulado en Celulares.

---

## 💡 Principales Conclusiones Comercial-Técnicas

1. **Volumen vs. Ingresos:** Un mayor volumen de ventas no garantiza mayores ingresos; categorías de alto ticket (como Celulares) generan más rentabilidad con menos transacciones.
2. **Uso Eficiente de SQL:** La combinación precisa de agregaciones y agrupamientos es indispensable para evitar sesgos en los resúmenes financieros.
3. **Prudencia en la Toma de Decisiones:** Evaluaciones basadas en muestras pequeñas (6 días) requieren complementarse con datos de stock y margen de ganancia antes de reasignar presupuestos.
