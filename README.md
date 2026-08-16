# Machine Learning con Python

Materiali, codice ed esempi pratici della **Lezione #01** del corso [Machine Learning con Python](https://www.ratataplan.it/corso-python-machine-learning.php) di Ratataplan.

📖 Lezione completa: [python-machine-learning-lezione-01.php](https://www.ratataplan.it/python-machine-learning-lezione-01.php)

## Contenuti

Il repository raccoglie i notebook Jupyter (`.ipynb`) utilizzati come esempi pratici nella lezione, ciascuno eseguibile direttamente su Google Colab senza bisogno di configurazione locale. Gli argomenti trattati spaziano dalle librerie di base per il data processing (NumPy, pandas, Matplotlib) alle quattro principali tipologie di machine learning: apprendimento supervisionato, non supervisionato, per rinforzo e semi-supervisionato.

## Esempi

| # | Notebook | Argomento | Descrizione |
|---|----------|-----------|-------------|
| 001 | [001_numpy.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/001_numpy.ipynb) | NumPy | Primi passi con NumPy e array: creazione, indicizzazione e operazioni vettoriali di base. |
| 002 | [002_pandas.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/002_pandas.ipynb) | pandas | Primi passi con pandas e DataFrame: creazione, indicizzazione e operazioni di base. |
| 003 | [003_matplotlib.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/003_matplotlib.ipynb) | Matplotlib | Primi passi con Matplotlib e visualizzazione dei dati: creazione di grafici per analizzare i dati. |
| 004 | [004_linear_regression.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/004_linear_regression.ipynb) | Apprendimento supervisionato | Introduzione alla regressione lineare con scikit-learn: training, test e calcolo dell'errore MSE. |
| 005 | [005_libraries.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/005_libraries.ipynb) | Librerie essenziali | Verifica della configurazione dell'ambiente con NumPy, pandas, Matplotlib e scikit-learn. |
| 006 | [006_linear_regression.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/006_linear_regression.ipynb) | Apprendimento supervisionato | Regressione lineare: flusso completo con visualizzazione dello split, dei parametri appresi e previsione su un dato nuovo. |
| 007 | [007_linear_regression.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/007_linear_regression.ipynb) | Apprendimento supervisionato | Caso reale: previsione del prezzo di affitto di un locale commerciale a partire dai metri quadri. |
| 008 | [008_kmeans.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/008_kmeans.ipynb) | Apprendimento non supervisionato | Clustering K-Means: raggruppamento di dati simili senza etichette su un dataset di esempio. |
| 009 | [009_kmeans.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/009_kmeans.ipynb) | Apprendimento non supervisionato | Caso reale: segmentazione automatica dei clienti in 3 gruppi con K-Means. |
| 010 | [010_rl.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/010_rl.ipynb) | Apprendimento per rinforzo | Il problema del bandito a più braccia (multi-armed bandit): esplorazione/sfruttamento e aggiornamento incrementale della stima. |
| 011 | [011_semi_supervised.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/011_semi_supervised.ipynb) | Apprendimento semi-supervisionato | Propagazione delle etichette con `LabelPropagation` su un piccolo dataset sintetico. |
| 012 | [012_semi_supervised.ipynb](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/012_semi_supervised.ipynb) | Apprendimento semi-supervisionato | Caso reale: `LabelSpreading` applicato al riconoscimento di cifre scritte a mano (dataset `digits`). |

## Come utilizzare i notebook

Ogni notebook è pensato per essere eseguito direttamente su **Google Colab**, senza bisogno di installare nulla in locale:

1. Clicca sul link del notebook desiderato nella tabella qui sopra.
2. Colab si aprirà automaticamente caricando il codice dal repository.
3. Esegui le celle in ordine (`Shift + Invio`) per seguire passo passo la spiegazione.

In alternativa, è possibile clonare il repository ed eseguire i notebook in locale:

```bash
git clone https://github.com/ratataplan/machine-learning.git
cd machine-learning
python -m venv .venv
source .venv/bin/activate  # su Windows: .venv\Scripts\activate
python -m pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook
```

## Librerie utilizzate

- [NumPy](https://numpy.org/) — calcolo numerico e array multidimensionali
- [pandas](https://pandas.pydata.org/) — manipolazione e analisi dei dati
- [Matplotlib](https://matplotlib.org/) — visualizzazione dei dati
- [scikit-learn](https://scikit-learn.org/) — algoritmi di machine learning

## Requisiti

- Python 3.10 o versioni successive

## Licenza e crediti

Materiale didattico a cura di [Carlo Mainardi](https://www.linkedin.com/in/carlomainardi) per [Ratataplan](https://www.ratataplan.it/) — Associazione di cultura informatica.

© 2005–2026 Ratataplan. Tutti i diritti riservati.
