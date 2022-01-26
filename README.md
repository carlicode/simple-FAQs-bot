
## Introducción
Este es un proyecto básico sobre la construcción de un bot en [RASA](https://rasa.com/) que responde un par de preguntas y respuestas sobe preguntas frecuentes de la página de la [Universidad Privada Boliviana](https://www.upb.edu/es/docs_admision)

## Tecnologías usadas
Anaconda
Python 3.8
Rasa 3

## Instalación

    conda create -n venv python =3.8
    conda activate
    python -m pip uninstall pip
    python -n pip ensurepip
    python -m pip install -U pip
    pip install rasa
    
## Uso

Comando para entrenar el modelo y usarlo en consola.

rasa train
rasa shell
