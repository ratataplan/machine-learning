# Machine Learning con Python

Esempi ed esercizi pratici del corso **Machine Learning con Python** di [ratataplan.it](https://www.ratataplan.it), la scuola di informatica del Circolo Ratataplan (Riccione, RN).

Ogni notebook è collegato direttamente alla lezione corrispondente sul sito e può essere aperto ed eseguito in Google Colab con un click, senza bisogno di installare nulla in locale.

📖 **Lezione di riferimento:** [Python Machine Learning — Lezione #01](https://www.ratataplan.it/python-machine-learning-lezione-01.php)

---

## Esercizi

| # | Notebook | Argomento | Apri |
|---|----------|-----------|------|
| 001 | [`001_numpy.ipynb`](001_numpy.ipynb) | Primi passi con NumPy e array — creazione, indicizzazione e operazioni vettoriali | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/001_numpy.ipynb) |
| 002 | [`002_pandas.ipynb`](002_pandas.ipynb) | Primi passi con pandas e DataFrame — creazione, indicizzazione e operazioni di base | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/002_pandas.ipynb) |
| 003 | [`003_matplotlib.ipynb`](003_matplotlib.ipynb) | Primi passi con Matplotlib — creazione di grafici e visualizzazione dei dati | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/003_matplotlib.ipynb) |
| 004 | [`004_sklearn.ipynb`](004_sklearn.ipynb) | Regressione lineare con scikit-learn — training, test ed errore MSE | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ratataplan/machine-learning/blob/main/004_sklearn.ipynb) |

---

## Come usare i notebook

### Opzione 1 — Google Colab (consigliata, zero installazione)
Clicca sul badge **"Open in Colab"** nella tabella sopra. Il notebook si apre già pronto all'uso nel browser. Per salvare le tue modifiche: **File → Save a copy in Drive**.

### Opzione 2 — In locale con VS Code
```bash
# Clona il repository
git clone https://github.com/ratataplan/machine-learning.git
cd machine-learning

# Crea e attiva un ambiente virtuale
python -m venv .venv
source .venv/bin/activate      # macOS/Linux
.venv\Scripts\activate         # Windows

# Installa le dipendenze
pip install numpy pandas matplotlib scikit-learn jupyter
```

Apri la cartella in VS Code e avvia i notebook con l'estensione Jupyter, oppure lancia Jupyter da terminale:

```bash
jupyter notebook
```

---

## Librerie utilizzate

- [NumPy](https://numpy.org/) — calcolo numerico e array multidimensionali
- [pandas](https://pandas.pydata.org/) — manipolazione e analisi dei dati
- [Matplotlib](https://matplotlib.org/) — visualizzazione dei dati
- [scikit-learn](https://scikit-learn.org/) — algoritmi di machine learning

---

## Corso completo

Questi esempi accompagnano il corso in aula **Machine Learning con Python**, che copre le basi del ML, Python per la data science, algoritmi supervisionati e non supervisionati, deep learning, NLP e deployment.

👉 [Scopri il corso su ratataplan.it](https://www.ratataplan.it/corso-python-machine-learning.php)

---

## Autore

**Carlo Mainardi** — [carlomainardi.com](https://www.carlomainardi.com) · [LinkedIn](https://www.linkedin.com/in/carlomainardi)

## Licenza

Materiale didattico distribuito a scopo formativo. Per usi diversi dalla didattica personale, contatta l'autore.
