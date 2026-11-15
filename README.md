# Edad cinemática de asociaciones estelares jóvenes con Gaia DR3

**Curso:** Minería de datos para astronomía  
**Fecha:** 15 de noviembre de 2026  
**Autor:** Carlos Eduardo Orozco Garcés

Este proyecto estudia la convergencia pasada de TW Hydrae. También analiza Upper Scorpius. La muestra se completa con Epsilon Chamaeleontis. Los datos provienen de SIMBAD y Gaia DR3. El cuaderno contiene las consultas ADQL. Las celdas posteriores procesan los datos y aplican un modelo de mezcla gaussiana.

## Archivos de la entrega

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corozco-personal/mineria_entrega_3/blob/main/proyecto_gaia.ipynb)

- [Ver el notebook en GitHub](proyecto_gaia.ipynb)
- [Descargar el notebook](https://raw.githubusercontent.com/corozco-personal/mineria_entrega_3/main/proyecto_gaia.ipynb)
- [Descargar el informe en PDF](https://raw.githubusercontent.com/corozco-personal/mineria_entrega_3/main/proyecto_gaia.pdf)
- [Consultar los archivos de datos](datos/)

## Carpeta `datos`

La carpeta contiene las respuestas de las consultas en formato CSV. Cada asociación tiene un archivo de miembros de SIMBAD. Otro archivo conserva el cruce con Gaia DR3. El tercer archivo contiene las fuentes evaluadas como candidatos.

| Prefijo | Asociación |
|---|---|
| `1_` | TW Hydrae |
| `2_` | Upper Scorpius |
| `3_` | Epsilon Chamaeleontis |

Los archivos `_simbad.csv` contienen los identificadores iniciales. Los archivos `_gaia.csv` guardan la astrometría usada en el análisis. Los archivos `_candidatos.csv` conservan las fuentes de la búsqueda de nuevos miembros.

## Ejecución

Abra el notebook con el botón de Google Colab y ejecute las celdas en orden. Los CSV permiten repetir el análisis sin enviar de nuevo todas las consultas. Para consultar las bases de datos otra vez, elimine los CSV antes de iniciar la ejecución.

## Fuente del curso

[Clase 12: Aprendizaje de Máquina No Supervisado](https://esilvavilla.github.io/MineriaDatosweb/Clase_12_Aprendizaje_No_Supervisado.html)
