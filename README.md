# MercadoLibre Crawler

Este proyecto utiliza Scrapy para rastrear artículos en la categoría de perros en Mercado Libre Ecuador. Es un ejemplo, pero se puede implementar para cualquier producto/país. 

## Descripción

El crawler está diseñado para:

- Extraer títulos, precios y descripciones de artículos.
- Navegar horizontalmente a través de la paginación de resultados y verticalmente hacia los detalles de los productos.

## Estructura del Proyecto

- **Articulo**: Define los campos para los artículos (título, precio, descripción).
- **MercadoLibreCrawler**: Spider que implementa la lógica de rastreo.

## Requisitos

- Python 3.x
- Scrapy
- BeautifulSoup

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/ruthsanchezp/mercadolibre-extractor-productos.git
