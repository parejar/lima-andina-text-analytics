# lima-andina-text-analytics
- Text analytics code for the [Lima Andina](https://limandina.org/ "Lima Andina") project.
- This is a selection of analysis and visualizations performed on the Lima Andina datasets that contain more than 6500 El Comercio newspaper ads published by internal migrants organizations in Lima between 1906 and 1933.
- We have made public two datasets, "Associations" and "Articles", through the [Borealis](https://doi.org/10.5683/SP2/8IPTYQ "El Comercio Migrant Association Database") repository.
- From the description in the Borealis repository:
> "The first contains information on the associations, and the second contains information on advertisements published in El Comercio by those associations. These announcements typically concerned upcoming and past meetings, elections and other association activities. In aggregate, the dataset reveals patterns in association activity that in turn illuminate the history of internal migration in early-20th century Peru."
- Table of contents
> 1. [Exploratory analysis and visualizations](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andia-exploracion-datos.ipynb)
> 2. [Pre-processing](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andia-preprocesamiento-texto.ipynb)
> 3. [Named Entities](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andina-entidades-nombradas.ipynb)
> 4. [Topic modelling](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andina-modelado-de-temas.ipynb)
> 5. [Syntactic similarity](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andina-similitud.ipynb)
> 6. [Embeddings](https://github.com/parejar/lima-andina-text-analytics/blob/main/lima-andina-ncrustaciones.ipynb)
- Example of a Tensorflow Embedding Projector visualization of semantic relationships in the corpus. [External link](https://projector.tensorflow.org/?config=https://gist.githubusercontent.com/parejar/ae23b9686f8fcee00091afdedb833025/raw/67548a65765cf0908fa64e7394eda7b665cf2e65/articulos_lima_andina_tensor.json)
  - Change the visualization settings to Uniform Manifold approximation and Projection (UMAP) for a more complete view of the embedding space.

<script src="https://gist.github.com/parejar/ae23b9686f8fcee00091afdedb833025.js"></script>

- DISCLAIMER: The code in this repository is made available only as a way of documenting the Digital Humanities side of the project. You can download the Jupyter notebooks and experiment with them at your own risk. The dataset that we used in these notebooks is different from the dataset available in Borealis but contain the same textual information in terms of the newspaper ads. Here we use a somewhat untidy dataset to illustrate data cleaning techniques.   
