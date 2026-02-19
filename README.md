# Desafío Alura Store - Análisis de Datos (Python)

## Descripción
Este proyecto realiza un análisis exploratorio y comparativo de 4 tiendas (Tienda 1 a Tienda 4) usando Python y Pandas, con el objetivo de generar insights para recomendar cuál tienda debería vender el Sr. Juan.

## Dataset
Los datos provienen de archivos CSV (uno por tienda), cargados en DataFrames:
- Tienda1
- Tienda2
- Tienda3
- Tienda4

Cada dataset incluye información de producto, categoría, precio, envío, calificaciones, fecha/ubicación de compra, tipo de pago y coordenadas geográficas.

## Análisis realizados
1. Ingreso total por tienda (suma de la columna Precio).
2. Ventas por categoría (conteo de ventas agrupadas por categoría).
3. Calificación promedio por tienda.
4. Productos más y menos vendidos por tienda.
5. Envío promedio por tienda.
Extra opcional:
- Análisis geográfico usando latitud y longitud.

## Visualizaciones
Se generaron al menos 3 gráficos con Matplotlib:
- Barras: ingreso total por tienda.
- Barras: calificación promedio por tienda.
- Barras: envío promedio por tienda.
(Adicionales: categorías top por tienda y dispersión geográfica).

## Tecnologías usadas
- Python 3
- Pandas
- Matplotlib

## Cómo ejecutar
1. Abrir el notebook en Google Colab.
2. Ejecutar las celdas de carga (código base).
3. Ejecutar las celdas de funciones y análisis.
4. Revisar tablas de resultados, gráficos y el informe final dentro del notebook.

## Notas
- El código incluye funciones para identificar nombres de columnas aunque varíen (por ejemplo: "Precio" vs "price").
- El análisis final recomienda una tienda considerando ingresos, satisfacción del cliente, ventas por categoría, rotación de productos y envío promedio.

## Autor
Sindy Campillo
