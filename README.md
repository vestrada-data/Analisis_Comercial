####  ANÁLISI COMERCIAL  - Proyecto Final 


 ## 🎯 Objetivo 

evaluar el rendimiento comercial global y los márgenes de ganancia de la operación, así como determinar la frecuencia de compra y el valor generado por usuario en los mercados de Argentina, México y Colombia. A través de este diagnóstico, se busca identificar ineficiencias operativas y formular recomendaciones estratégicas para proteger la rentabilidad del negocio.

## 🛠️ Herramientas Utilizadas
Python (Pandas, NumPy), SQL, Power BI (DAX, Power Query), Modelado ETL, Data Storytelling.

Preguntas del negocio:<br>
¿Cómo ha evolucionado el ingreso total entre 2024 y 2025?<br>
¿Qué segmentos de clientes aportan mayor ingreso y rentabilidad?<br>
¿Qué categorías de producto tienen mayor impacto en el negocio?<br>
¿Existen diferencias relevantes entre países o regiones?<br>
¿Qué patrones temporales se observan a lo largo del año?<br>
¿Dónde podrían existir oportunidades de mejora comercial?<br>

## KPIs monitoreados
Ingresos Totales: porque me permite saber el tamaño del mercado capturado, es el indicador del volumen del negocio.<br>
Ventas: Nos ayuda a entender si el crecimiento del ingreso se debe a que estamos vendiendo mas volumen de producto. .<br>
Rentabilidad: Este KPI mide la eficiencia de la operación retail.

## Proceso realizado
- Conexión y Exploración de los Datos 
- Limpieza y transformación de datos
- Validación de Calidad
- Funnel (SQL)
- Retención (SQL)
- Medición de cambios - Experimentación (Python)
- Modelado de Datos y Tabla de Tiempos
- Creación de métricas en DAX
- Diseño y planificación
- Diseño de dashboard ejecutivo
- Generación de insights para toma de decisiones
- Narrativa del Dashboard 

Principales insights:
1. La operación de la empresa presenta un riesgo de concentración crítico. Al depender casi en su totalidad de la categoría 'Electrónica' (y específicamente de la venta de hardware de alta gama), el flujo del negocio es altamente vulnerable a factores externos incontrolables. El incremento en los aranceles de importación en América Latina o una desaceleración en el consumo de bienes durables impactaría de forma inmediata y severa las finanzas de la empresa. Las categorías de 'Hogar' y 'Moda' se encuentran actualmente subutilizadas, desaprovechando su potencial como amortiguadores de ingresos.
2. El éxito comercial del producto Laptop-Gaming-16GB está subsidiando una pérdida invisible; el sistema actual permite aplicar descuentos ciegos que destruyen el margen neto.
3. La baja conversión de México no es un problema de demanda o de mercado (pues el volumen de ventas es casi idéntico al de Argentina), sino el síntoma directo de la distorsión de precios de la Laptop-Gaming-16GB. El mercado mexicano está absorbiendo el volumen de transacciones en pérdida, erosionando el margen del país.

