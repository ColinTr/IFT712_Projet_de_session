IFT712_Projet_de_session
==============================

Projet Session Techniques Apprentissage

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │       ├── train      <- Data used to train the model.
    │       └── test       <- Data used to test the model.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── gestion_donnees.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make predictions
    │   │   ├── generatif_et_fischer.py
    │   │   ├── methodes_a_noyau.py
    │   │   ├── perceptron.py
    │   │   ├── regression_logistique.py
    │   │   ├── reseaux_de_neurones.py
    │   │   ├── machines_a_vecteurs_de_support.py
    │   │   └── utilitaire_validation_croisee.py
    │   │
    │   ├── visualization  <- Scripts to create exploratory and results oriented visualizations
    │   │   └── visualize.py
    │   │
    │   └── main.py        <- main script that launches everything needed to generate the results
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>