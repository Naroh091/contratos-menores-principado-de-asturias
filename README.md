# Contratos Menores del Principado de Asturias

## Propósito

Este repositorio existe para publicar los contratos menores del Principado de Asturias en un formato reutilizable. La forma en que el Principado publica actualmente estos datos dificulta poder utilizar la información de forma sencilla.

**Fuente original:** [Relaciones trimestrales de contratos menores celebrados - miPrincipado](https://miprincipado.asturias.es/-/relaciones-trimestrales-de-contratos-menores-celebrados)

## Proceso Técnico

Los datos pasan por un proceso de scraping, procesamiento y normalización que incluye:

- **Lenguaje:** Python
- **Extracción de tablas:** [Camelot](https://camelot-py.readthedocs.io/) para extraer las tablas de los documentos PDF
- **Normalización de datos:** Google Gemini para matchear las columnas del documento original al modelo de datos normalizado

Este proceso automatizado permite transformar los PDFs publicados por el Principado en datos estructurados y fácilmente reutilizables.
