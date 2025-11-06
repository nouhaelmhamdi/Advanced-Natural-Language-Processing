# Analyse de Sentiments sur les Commentaires (YouTube)

Ce dossier contient un notebook pédagogique `main.ipynb` pour un atelier d'analyse de sentiments / détection de spam sur des commentaires YouTube.

## Contenu

- `main.ipynb` — Notebook principal (prétraitement, MLP et RNN simple, visualisations).
- `data/` — fichiers CSV originaux de commentaires YouTube.
- `requirements.txt` — dépendances Python recommandées pour exécuter le notebook.

## Prérequis

- Python 3.8+ (recommandé)
- Espace disque suffisant pour installer TensorFlow si vous utilisez l'accélération GPU.

## Installation (PowerShell)

Ouvrez PowerShell, placez-vous dans ce dossier puis exécutez :

```powershell
# Créer et activer un environnement virtuel
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# Mettre pip à jour
pip install -U pip

# Installer les dépendances listées
pip install -r "c:\Users\HP\Career\MASTER ML&AI\Advanced Natural Language Processing\Advanced-Natural-Language-Processing\Analyse de Sentiments sur les Commentaires\requirements.txt"
```

Notes:

- Si vous préférez une installation CPU-only (par ex. pour éviter les paquets GPU de TensorFlow), utilisez `tensorflow-cpu` à la place de `tensorflow` dans le `requirements.txt`.
- `jupyter` et `ipykernel` sont inclus dans `requirements.txt` pour exécuter/ouvrir le notebook.

## Lancer le notebook

Après l'installation, lancez :

```powershell
jupyter notebook "main.ipynb"
```

ou ouvrez `main.ipynb` directement dans VS Code (avec l'extension Jupyter).

## Remarques

- Les versions dans `requirements.txt` sont des minimums conservateurs (>=) ; si vous voulez des versions figées, générez un `pip freeze` depuis votre environnement et je peux créer un fichier verrouillé.
- Le notebook lit les CSV dans `data/`. Assurez-vous que les fichiers CSV s'y trouvent (ou adaptez les chemins dans le notebook si nécessaire).
