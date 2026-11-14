# Architecture Transformer

Notebooks pédagogiques pour explorer les modèles de séquences et les modèles de langage avec PyTorch et Transformers.

## Parcours conseillé

| Ordre | Notebook | Sujet |
| --- | --- | --- |
| 1 | [RNN](notebooks/sequence_models/RNN.ipynb) | Prédire une série sinusoïdale avec un réseau récurrent simple. |
| 2 | [LSTM](notebooks/sequence_models/LSTM.ipynb) | Réaliser la même prédiction avec une mémoire LSTM. |
| 3 | [Transformer](notebooks/sequence_models/Transformer.ipynb) | Utiliser un encodeur Transformer et des positions apprises. |
| 4 | [BERT](notebooks/language_models/BERT.ipynb) | Prédire un token masqué avec BERT multilingue. |
| 5 | [GPT](notebooks/language_models/GPT.ipynb) | Générer du texte avec GPT-2. |

Chaque notebook est autonome : exécuter ses cellules dans l'ordre, du début à la fin.

## Installation

Prérequis : Python 3.11 ou supérieur et [uv](https://docs.astral.sh/uv/).

```sh
uv sync --locked
```

Ouvrir un notebook dans VS Code avec les extensions Python et Jupyter, puis sélectionner l'interpréteur du dossier `.venv` comme noyau.

Les notebooks RNN, LSTM et Transformer génèrent leurs données avec PyTorch. Les notebooks BERT et GPT téléchargent leurs modèles préentraînés au premier lancement et nécessitent alors une connexion Internet.
