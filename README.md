# Plantilla de Proyecto de Data Science

## Estructura
- **data/** → datasets (CSV, Excel, JSON…)
- **notebooks/** → notebooks de análisis
- **src/** → funciones y scripts reutilizables
- **requirements.txt** → librerías necesarias para el proyecto

## Cómo iniciar un proyecto nuevo basado en esta plantilla
1. Copiar esta carpeta:
   cp -R plantilla_datascience nuevo_proyecto

2. Crear y activar el entorno virtual:
   python3.13 -m venv venv
   source venv/bin/activate

3. Instalar librerías:
   pip install -r requirements.txt
