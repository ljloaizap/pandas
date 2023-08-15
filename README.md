# Pandas journey

Let's get started with some coding around Pandas and whatever we need to process the data, analyze it, get the most of it and provide gold value for a better world... starting by our own :sunglasses:


# Chatcito's recommendations (in Spanish)
1. **Pandas Cookbook" en Kaggle:** Este recurso ofrece una serie de tutoriales interactivos que cubren varios aspectos de Pandas y su aplicación en el procesamiento de datos. Puedes acceder a ellos de forma gratuita en el siguiente enlace: Pandas Cookbook
2. **"Introduction to Data Science in Python" en Coursera:** Este curso proporcionado por la Universidad de Míchigan ofrece una introducción a la ciencia de datos en Python, incluyendo el uso de Pandas para el procesamiento y análisis de datos. Puedes acceder a la versión auditada de forma gratuita. Introduction to Data Science in Python
3. **"Data Wrangling with Pandas" en DataCamp:** Este curso en DataCamp se centra en el procesamiento y limpieza de datos utilizando Pandas. Ofrece lecciones interactivas y ejercicios prácticos para ayudarte a dominar las habilidades de manipulación de datos. Puedes acceder a una versión gratuita de prueba por un tiempo limitado. Data Wrangling with Pandas
4. **"Data Manipulation with pandas" en Real Python:** Este tutorial en línea gratuito de Real Python proporciona una introducción detallada a Pandas y su uso para manipular y analizar datos. Cubre una variedad de temas, desde la lectura de datos hasta la agregación y agrupación. Data Manipulation with pandas
5. **"Pandas Tutorial" en PyData:** PyData ofrece una serie de tutoriales en línea, incluyendo uno dedicado a Pandas. Este tutorial cubre los conceptos básicos de Pandas y ofrece ejemplos prácticos de su uso en el procesamiento de datos. Pandas Tutorial

# Developer jungle :deciduous_tree:
## Notebook kernel
```
> pipenv install jupyter
> pipenv install ipykernel
> pipenv run python -m ipykernel install --user --name=pandasprom
> jupyter notebook  # init jupyter

--

> jupyter kernelspec list
> jupyter kernelspec uninstall pandasprom
```

# Issues / Knowledge Base
1. Unicode decode error: `encoding`
    ```
    > UnicodeDecodeError: 'utf-8' codec can't decode byte 0xe9 in position 15: invalid continuation byte
    
    df = pd.read_csv('../data/bikes_montreal_2012.csv', **encoding='ISO-8859-1'**)
    ```

2. Mixed types: `dtype`
    ```
    > DtypeWarning: Columns (8) have mixed types. Specify dtype option on import or set low_memory=False.

    df_complaints = pd.read_csv('../data/311-service-requests.csv', dtype='unicode')
    ```

# Useful links
- **Github repository**: [pandas-cookbook](https://github.com/jvns/pandas-cookbook/blob/master/data/bikes.csv)
- **Kaggle**: Excellent Pandas Notebooks from book Pandas Cookbook: [discussion](https://www.kaggle.com/discussions/getting-started/120943)
