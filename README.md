# Análisis Descriptivo de Libros usando Web Scraping

Este proyecto realiza un análisis descriptivo de libros utilizando datos obtenidos mediante técnicas de web scraping del sitio [toscrape.com](http://books.toscrape.com/). La página contiene más de 800 libros distribuidos en más de 40 categorías y está estructurada de manera sencilla, lo que facilita la extracción de datos como títulos, precios y categorías.

## Descripción del Proyecto

El objetivo de este proyecto es:

1. **Extracción de Datos**: Obtener información relevante de libros, como títulos, precios y categorías, mediante web scraping.
2. **Limpieza de Datos**: Procesar los datos extraídos para asegurar su calidad y consistencia.
3. **Análisis Descriptivo**: Realizar un análisis descriptivo de los datos para obtener una comprensión más profunda del conjunto de libros.

## Estructura del Proyecto

- `src/`: Contiene los scripts de scraping y análisis.
- `data/`: Carpeta donde se almacenan los datos extraídos y limpiados.
- `notebooks/`: Notebooks de Jupyter con el análisis detallado.
- `README.md`: Explicación general del proyecto.

## Requisitos

- Python 3.x
- Bibliotecas necesarias: BeautifulSoup, Requests, Pandas, entre otras. Las dependencias completas están listadas en `requirements.txt`.

## Ejecución

1. Clona este repositorio: `git clone https://github.com/usuario/proyecto-scraping.git`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta el script de scraping: `python src/scraping.py`
4. Ejecuta el análisis descriptivo desde los notebooks en `notebooks/`

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.
