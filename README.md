# Proyecto Básico de Procesamiento de Lenguaje Natural (NLP)  

Este proyecto tiene como objetivo aplicar técnicas básicas de procesamiento de lenguaje natural (NLP) sobre dos conjuntos de datos: un **dataframe de tweets** y un **libro de Harry Potter** alojado en un archivo `.txt`. Se emplean diversas herramientas para la **limpieza, manipulación y análisis** del lenguaje.

---

## Descripción  

### 1. **Manipulación de Tweets**  
- **Limpieza de datos:** Uso de **expresiones regulares (regex)** para eliminar enlaces, menciones, hashtags, y caracteres no deseados.  
- **Lematización:** Reducción de palabras a su forma base utilizando herramientas NLP.  
- **Vectorización:** Conversión de los textos en representaciones numéricas (con **TF-IDF**).  
- **Visualización:** Creación de gráficos para mostrar las palabras más frecuentes en los tweets procesados.

### 2. **Análisis del Libro de Harry Potter**  
- **Uso de Stopwords con spaCy:** Filtrado de palabras vacías (como "y", "el", "de") para mejorar la calidad del análisis y filtrado de palabras requeridas como nombres y lugares.  
- **Visualización con nubes de palabras:** Generación de **nubes de palabras** para destacar las palabras más frecuentes en el texto.
