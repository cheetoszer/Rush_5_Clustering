# Rush4

Ines je veux un 20. Attention quand tu exec les cellules de recherche des paramètres optimaux. C'est pas nécéssaire et c'est très long.

## Prérequis

- **Python 3.6+** doit être installé sur votre machine.
- Assurez-vous d'avoir installé `pip` pour la gestion des packages Python.
- Un environnement virtuel est recommandé pour éviter les conflits de dépendances.

## Installation

### Projet

1. Télécharger le projet par HTTPS :
    ```bash
    git clone https://github.com/cheetoszer/Rush_5_Clustering.git
    ```

2. Télécharger le projet par ssh :
    ```bash
    git clone git@github.com:cheetoszer/Rush_5_Clustering.git
    ```

### Windows

1. Déplacez vous dans le répertoire du projet :
    ```bash
    cd Rush_5_Clustering
    ```

2. Créez et activez l'environnement virtuel :
    ```bash
    python3 -m venv .venv
    .\.venv\Scripts\activate
    ```

3. Installez les dépendances :
    ```bash
    python3 -m pip install -r requirements.txt
    ```

4. (Optionnel) Si vous utilisez VS Code, vous pouvez ouvrir l'éditeur avec :
    ```bash
    code .
    ```

### Linux / MacOS

1. Déplacez vous dans le répertoire du projet :
    ```bash
    cd Rush_5_Clustering
    ```

2. Créez et activez l'environnement virtuel :
    ```bash
    python3 -m venv .venv
    source ./.venv/bin/activate
    ```

3. Installez les dépendances :
    ```bash
    python3 -m pip install -r requirements.txt
    ```

4. (Optionnel) Si vous utilisez VS Code, vous pouvez ouvrir l'éditeur avec :
    ```bash
    code .
    ```

## Utilisation

Dans test.ipynb se trouve la plupart de mes recherches.
Dans chaque dossier, deux modèles, un avec les données d'entraînement rééchantillonnées, l'autre entraîné sur la data normale.
Benchmark.ipynb est un comparatif des performances des différents modèles.