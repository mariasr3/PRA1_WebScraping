# Pràctica 1: Web Scraping 
*Autores:* **Joana Llauradó Pont, Maria Sopena Rios**

*Novembre 2023*
## “Obres de teatre a Barcelona” 
En aquesta pràctica s’elabora un cas pràctic orientat a aprendre a identificar i extreure dades rellevants per a un projecte analític, fent servir eines específiques de web scraping. En aquest cas, extraiem informació sobre obres de teatre de la pàgina web Teatre Barcelona (https://www.teatrebarcelona.com/) 

### Arxius 
- **README.md**
- **source/main.py**: codi per realitzar el web scrapping
- **source/functions.py**: funció per cada extreure columna/camp que trobem al dataset final
-  **source/parameters.py**: paràmetres per fer una advance search. L'usuari pot seleccionar la data, ell lloc, el tipus d'obra, el rang de preu i a més pot especificar l'ordre.
- **asource/requirements.txt**: conté una llista les llibreries necessàries per executar el codi
- **data/teatre_novembre_2023.csv**: dataset resultant del córrer el codi

### Execució

```{r, engine='bash', code_block_name} 
pip install jupyter
pip install notebook 
jupyter notebook teatre_bcn.ipynb
```


### Dataset 
El dataset *teatre_novembre_2023.csv* està disponible a Zenodo.
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10123665.svg)](https://doi.org/10.5281/zenodo.10123665)
