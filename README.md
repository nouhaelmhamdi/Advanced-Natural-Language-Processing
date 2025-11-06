# Advanced Natural Language Processing

This repository contains notebooks and resources for the "Advanced Natural Language Processing" course materials and exercises.

Contents

- `main.ipynb` — top-level notebook (course overview / experiments).
- `Analyse de Sentiments sur les Commentaires/` — sentiment analysis project with data, a notebook, and related resources.
- `Langage N-gram pour générer un texte/` — (project folder for N-gram text generation).

Quick start

1. Create and activate a Python virtual environment (recommended):

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

2. Install dependencies (from the repository root):

   ```powershell
   pip install -r requirements.txt
   ```

3. Open the notebooks using Jupyter or VS Code:

   - To start Jupyter Notebook:

     ```powershell
     jupyter notebook
     ```

   - Or open this folder in VS Code and open the `.ipynb` files.

Data

Sample data for the sentiment analysis notebook is in:

`Analyse de Sentiments sur les Commentaires/data/`

Notes

- The `requirements.txt` at the repository root includes the packages required to run the notebooks.
- If you need a CPU-only TensorFlow build, uncomment or change the `tensorflow` line in `requirements.txt`.
