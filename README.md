# Student Performance Predictions — APC 2026

Estructura inicial segons els documents de l’assignatura. Base de dades seleccionada: Student Performance Predictions. Encara no s’han entrenat models ni obtingut resultats.

## Base de dades i pregunta

**Nom exacte:** Student Performance Predictions

**Kaggle:** https://www.kaggle.com/datasets/haseebindata/student-performance-predictions

**Publicador:** haseebindata.

Pendent de verificar els fitxers i la llicència abans de concretar la variable objectiu i la pregunta del projecte.

## Estructura

- `data/`: dades originals i documentació de la descàrrega.
- `notebooks/01_exploration.ipynb`: exploració i interpretació dels atributs.
- `notebooks/02_models.ipynb`: comparativa i avaluació.
- `src/`: codi reutilitzable i configuració.
- `models/`: models generats (no versionats).

## Preparació

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Els notebooks són plantilles inicials. Encara no constitueixen l’anàlisi final executable.
Llavor prevista: 42. Separar train/test abans d’ajustar transformacions; fer el preprocessament dins de pipelines. Comparar una baseline i almenys quatre models amb validació creuada i cerca d’hiperparàmetres només amb train. Reservar test per a una única avaluació final.

## Resultats

Pendents de realitzar l’estudi.

## Publicació i entrega

Pendent de crear el repositori remot i afegir `silvanasp` com a col·laboradora. L’entrega inicial demana el nom exacte de la base de dades i l’enllaç del repositori del grup.

## Declaració d’ús d’IA

S’ha utilitzat Codex per llegir l’enunciat i preparar l’estructura inicial del repositori.
