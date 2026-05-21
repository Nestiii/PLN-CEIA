# PLN-CEIA

Repositorio para la materia **Procesamiento del Lenguaje Natural I** de la Carrera de Especialización en Inteligencia Artificial (CEIA - FIUBA).

Acá voy a ir resolviendo y subiendo los desafíos de la cursada. Cada desafío vive en su propio directorio con la notebook correspondiente y, si hace falta, datos auxiliares y un README específico.

## Estructura

- `desafio_1/` — Vectorización de texto (TF-IDF), similaridad de documentos, clasificación zero-shot por prototipos y Naïve Bayes sobre el dataset **20 Newsgroups**.
- `desafio_2/` — Custom word embeddings con **Gensim/Word2Vec** sobre las letras de **Bob Dylan**: términos más y menos similares, reducción a 2D con t-SNE y análisis de los grupos de palabras que se forman.

## Stack

- Python 3
- `scikit-learn`, `numpy`, `pandas`
- `gensim`, `matplotlib`
- Jupyter Notebooks

## Cómo correr las notebooks

```bash
pip install numpy pandas scikit-learn gensim matplotlib jupyter
jupyter notebook
```

Después abrir la notebook del desafío que quieras correr desde su carpeta.

## Autor

Facundo Rivas — CEIA, FIUBA.
