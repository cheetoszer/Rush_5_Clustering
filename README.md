# Rush4

Ines je veux un 20. Attention quand tu exec les cellules de recherche des paramètres optimaux. C'est pas nécéssaire et c'est très long.

## Prérequis

- **Python 3.6+** doit être installé sur votre machine.
- Assurez-vous d'avoir installé `pip` pour la gestion des packages Python.
- Un environnement virtuel est recommandé pour éviter les conflits de dépendances.

## Installation

### Windows

1. Créez et activez l'environnement virtuel :
    ```bash
    python3 -m venv .venv
    .\.venv\Scripts\activate
    ```

2. Installez les dépendances :
    ```bash
    python3 -m pip install -r requirements.txt
    ```

3. (Optionnel) Si vous utilisez VS Code, vous pouvez ouvrir l'éditeur avec :
    ```bash
    code .
    ```

### Linux / MacOS

1. Créez et activez l'environnement virtuel :
    ```bash
    python3 -m venv .venv
    source ./.venv/bin/activate
    ```

2. Installez les dépendances :
    ```bash
    python3 -m pip install -r requirements.txt
    ```

3. (Optionnel) Si vous utilisez VS Code, vous pouvez ouvrir l'éditeur avec :
    ```bash
    code .
    ```

## Utilisation

Dans test.ipynb se trouve la plupart de mes recherches.
Dans chaque dossier, deux modèles, un avec les données d'entraînement rééchantillonnées, l'autre entraîné sur la data normale.
Benchmark.ipynb est un comparatif des performances des différents modèles.