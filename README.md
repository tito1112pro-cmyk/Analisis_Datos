# EA3 — Comparación climática con NumPy

Trabajo individual: Nicolás Restrepo. Compara Medellín (Colombia) y Ciudad de México (México), con datos diarios de 2024 del reanálisis ERA5 de Open-Meteo.

## Estructura
- `EA3_Restrepo_Nicolas.ipynb`: informe, fuentes, revisión de calidad, NumPy, máscaras, broadcasting, tres figuras y conclusiones.
- `datos/`: los CSV se descargan automáticamente en la primera ejecución, a partir de las URL impresas en el notebook.
- `graficas/`: se guardan tres PNG al ejecutar.
- `resumen_*.csv` y `resumen_resultados.txt`: se generan al ejecutar.

## Ejecución necesaria para obtener resultados REALES
1. Abrir el notebook en Jupyter o Google Colab con conexión a internet y ejecutar todas las celdas en orden. En Colab, los CSV se guardan dentro del espacio de ejecución; para incluirlos en GitHub, descargarlos junto con el notebook.
2. Guardar el notebook con sus salidas numéricas y gráficas, y subir toda la carpeta `EA3_comparacion_climatica/` al repositorio EA1 de GitHub.
3. Instalar dependencias si hace falta: `pip install -r requirements.txt`.

**Importante:** No se incluyen datos ficticios. Este paquete no trae CSV ni resultados precalculados porque el entorno de producción no pudo consultar la API de datos. La ejecución conectada es imprescindible antes de presentar el trabajo como terminado.

Fuente: https://open-meteo.com/en/docs/historical-weather-api
