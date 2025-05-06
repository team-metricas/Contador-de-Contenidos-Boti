# Contador-de-Contenidos-Boti
Este proyecto contiene un notebook de Jupyter titulado **`Contador de Contenidos.ipynb`**, que permite analizar y para contar Intenciones y Contenidos (cuxes) y compararlos con algún periodo anterior de relevancia para ver cómo ha variado

## 📋 Descripción

El notebook realiza las siguientes funciones principales:

* Carga de datos desde una fuente específica (CSV, Excel u otra).
* Conteo de elementos únicos por categoría o tipo.
* Visualización de resultados .
* Filtrado y agrupación por distintos criterios .

## ⚙️ Requisitos

Asegúrate de tener instalado lo siguiente:

* Python 3.7 o superior
* Jupyter Notebook
* Pandas
* Matplotlib / Seaborn (si hay visualizaciones)
* openpyxl (si se carga desde Excel)

Puedes instalar los paquetes necesarios con:

```bash
pip install pandas matplotlib seaborn openpyxl
```

## 🚀 Cómo usar

1. Clona este repositorio o descarga el archivo `.ipynb`.
2. Abre el notebook con Jupyter:

```bash
jupyter notebook Contador\ de\ Contenidos.ipynb
```

3. Ejecuta las celdas una por una para procesar y visualizar los datos.
4. Modifica los parámetros según tus necesidades (como rutas de archivos o columnas de interés).

## 📁 Estructura esperada de los datos

Asegúrate de que el archivo que vas a analizar tenga las siguientes columnas clave (ejemplo):

* `Tipo de contenido`
* `Fecha`
* `Categoría`
* `Nombre del archivo`

## 📝 Notas

* El notebook puede adaptarse fácilmente a otros contextos de conteo de contenidos.
* Se recomienda revisar el formato de fechas y nombres para evitar errores de análisis.
